Folder structure
```
edunovaa.workspace/
├── index.html            Login screen
├── dashboard.html        Dashboard
├── customers.html        Customer page
├── README.md
└── assets/
    ├── css/
    │   ├── base.css      Design tokens, buttons, inputs, badges, modal, toast
    │   ├── login.css     Login screen styles
    │   └── app.css       App shell (sidebar, header), cards, tables, responsive rules
    └── js/
        ├── data.js       Mock data + tiny data store
        ├── utils.js      Icons, formatters (₹, dates), badges, toast, modal helper
        ├── auth.js       Front-end login / logout / route guard
        ├── layout.js     Renders sidebar + top header on every app page
        ├── login.js      Login page logic & validation
        ├── dashboard.js  Summary cards, requests table, breakdowns
        └── customers.js  List, search, filter, add customer, details modal
