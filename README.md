<h1>⚛️ goit-react-hw-01 — React Components</h1>

<p>
This project is part of the GoIT React curriculum.
It focuses on building reusable <b>React components</b>, working with <b>props</b>,
component composition, and basic project structure using <b>Vite</b>.
</p>

<hr />

<h2>🎯 Project Requirements</h2>
<ul>
  <li>Create a repository named <b>goit-react-hw-01</b></li>
  <li>Build the project using <b>Vite</b></li>
  <li>Deploy the project and provide a <b>Vercel live link</b></li>
  <li>No errors or warnings in the browser console</li>
  <li>Use <b>default export</b> for all components</li>
  <li>All components must be rendered inside the <code>&lt;App&gt;</code> component</li>
  <li>All props must be passed correctly</li>
  <li>Code must be clean, readable, and formatted with <b>Prettier</b></li>
  <li>Styles must be implemented using <b>CSS Modules</b></li>
</ul>

<hr />

<h2>🛠️ Technologies Used</h2>
<ul>
  <li><b>React</b> — Component-based UI</li>
  <li><b>Vite</b> — Fast project setup and build tool</li>
  <li><b>JavaScript (ES6+)</b></li>
  <li><b>CSS Modules</b> — Scoped component styles</li>
  <li><b>Prettier</b> — Code formatting</li>
</ul>

<hr />

<h2>📂 Project Structure</h2>

<pre>
src/
 ├── components/
 │   ├── Profile/
 │   │   ├── Profile.jsx
 │   │   └── Profile.module.css
 │   ├── FriendList/
 │   │   ├── FriendList.jsx
 │   │   └── FriendList.module.css
 │   ├── FriendListItem/
 │   │   ├── FriendListItem.jsx
 │   │   └── FriendListItem.module.css
 │   ├── TransactionHistory/
 │   │   ├── TransactionHistory.jsx
 │   │   └── TransactionHistory.module.css
 ├── App.jsx
 ├── userData.json
 ├── friends.json
 └── transactions.json
</pre>

<hr />

<h2>📌 Task 1 — Social Media Profile</h2>

<p>
The <b>Profile</b> component displays user information using props:
</p>

<ul>
  <li><code>name</code> — user name</li>
  <li><code>tag</code> — social tag without @</li>
  <li><code>location</code> — city and country</li>
  <li><code>image</code> — avatar URL</li>
  <li><code>stats</code> — followers, views, likes</li>
</ul>

<p>
User data is stored in <code>userData.json</code> and imported into <code>App.jsx</code>.
</p>

<hr />

<h2>📌 Task 2 — Friend List</h2>

<p>
The <b>FriendList</b> component renders a list of friends based on an array of objects.
Each friend is displayed using the <b>FriendListItem</b> component.
</p>

<ul>
  <li><code>avatar</code> — avatar image</li>
  <li><code>name</code> — friend name</li>
  <li><code>isOnline</code> — online status (true / false)</li>
</ul>

<p>
Friend data is stored in <code>friends.json</code>.
Online status is styled conditionally using CSS classes.
</p>

<hr />

<h2>📌 Task 3 — Transaction History</h2>

<p>
The <b>TransactionHistory</b> component displays banking transactions in a table.
</p>

<ul>
  <li><code>id</code> — unique transaction identifier</li>
  <li><code>type</code> — transaction type</li>
  <li><code>amount</code> — transaction amount</li>
  <li><code>currency</code> — currency code</li>
</ul>

<p>
Transaction data is stored in <code>transactions.json</code> and rendered dynamically.
</p>

<hr />

<h2>🚀 Deployment</h2>
<ul>
  <li>The project is deployed using <b>Vercel</b></li>
  <li>Two links are provided for submission:</li>
  <ul>
    <li>GitHub repository (source code): https://kutluhangil.github.io/goit-react-hw-01/ </li>
    <li>Vercel live project link: https://goit-react-hw-01-rose-one.vercel.app </li>
  </ul>
</ul>

<hr />

<h2>✅ Final Notes</h2>
<p>
This project demonstrates core React fundamentals such as component composition,
props usage, reusable UI blocks, and clean project structure.
It serves as a foundation for more advanced React topics.
</p>

<p><b>Happy coding! 🚀</b></p>
