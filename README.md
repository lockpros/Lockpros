## Hi there 👋

<!--
**lockpros/Lockpros** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
// pages/index.js
import Link from 'next/link'

export default function Home() {
  return (
    <div className="min-h-screen flex flex-col justify-center items-center bg-gray-50">
      <h1 className="text-4xl font-bold text-blue-800">Lockpros AI Suite</h1>
      <p className="mt-4 text-lg text-gray-700">
        Your AI-powered locksmith platform is live!
      </p>
      <div className="mt-8 space-x-4">
        <Link href="/signup">
          <a className="px-6 py-3 bg-yellow-500 text-white rounded hover:bg-yellow-600">
            Start Free Trial
          </a>
        </Link>
        <Link href="/dashboard">
          <a className="px-6 py-3 border border-blue-800 text-blue-800 rounded hover:bg-blue-100">
            Admin Dashboard
          </a>
        </Link>
      </div>
    </div>
  )
}
