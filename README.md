# Learn WebdriverIO & Mocha 🚀

This repository is dedicated to learning and practicing automated end-to-end testing using **WebdriverIO** with the **Mocha** test framework.

## 🛠 Tech Stack

- **Framework:** [WebdriverIO](https://webdriver.io/) (v9+)
- **Test Runner:** [Mocha](https://mochajs.org/)
- **Assertion Library:** [Expect-WebdriverIO](https://webdriver.io/docs/api/expect-webdriverio)
- **Language:** JavaScript (ES Modules)
- **Pattern:** Page Object Model (POM)

## 📋 Prerequisites

Before running the tests, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (Version 18 or higher recommended)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)

## 🚀 Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/jordanprepos/learn-webdriverio.git
   cd learn-webdriverio
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

## 🧪 Running Tests

To run all tests in the project:

```bash
npm run wdio
```

This will:

- Initialize the WebdriverIO runner.
- Execute the specs defined in `wdio.conf.js`.
- Use the local Chrome browser by default.

## 📂 Project Structure

```text
.
├── test/
│   ├── pageobjects/    # Selectors and page-specific logic (POM)
│   └── specs/          # Test files (Mocha 'it' and 'describe' blocks)
├── wdio.conf.js        # Main configuration file
├── package.json        # Project dependencies and scripts
└── README.md           # You are here!
```

## 📚 Resources

- [WebdriverIO Official Documentation](https://webdriver.io/docs/gettingstarted)
- [Mocha Getting Started](https://mochajs.org/#getting-started)
- [Node.js Documentation](https://nodejs.org/en/docs/)

---

Happy Testing! 🤖
