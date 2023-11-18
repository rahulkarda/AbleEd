<h1 align="center">
  <a href="https://github.com/rahulkarda">
    <img src="https://github.com/rahulkarda/uia/blob/master/public/learn-together.png?raw=true" alt="Learn Together" width="150" >
  </a>
</h1>


<div align="center">

**Latest Prototype Screenshots**

<!-- <img src="https://github.com/rahulkarda/assets/blob/main/thinkbig/readme-md/thinkbig-screenshot-1.webp" title="Prototype Classes Page" width="250px">  -->
<img src="https://github.com/100Devs-ADHD/assets/blob/main/thinkbig/readme-md/thinkbig-screenshot-2.webp" title="Prototype Classes Page" width="250px"> <img src="https://github.com/100Devs-ADHD/assets/blob/main/thinkbig/readme-md/thinkbig-screenshot-3.webp" title="Prototype Calendar" width="250px">
<br />
<br />
<a href="https://github.com/rahulkardaissues/new?assignees=&labels=bug&template=01_BUG_REPORT.md&title=bug%3A+">Report a Bug</a>
·
<a href="https://github.com/rahulkardaissues/new?assignees=&labels=enhancement&template=02_FEATURE_REQUEST.md&title=feat%3A+">Request a Feature</a>
·
<a href="https://github.com/rahulkardadiscussions">Ask a Question</a>

</div>

<div align="center">
<br />

[![Project license](https://img.shields.io/github/license/100Devs-ADHD/think-big.svg?style=flat-square)](LICENSE)

[![Pull Requests welcome](https://img.shields.io/badge/PRs-welcome-ff69b4.svg?style=flat-square)](https://github.com/rahulkarda/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22)
[![code with love by Rahul](https://img.shields.io/badge/%3C%2F%3E%20with%20%E2%99%A5%20by-100DevsADHD-ff1414.svg?style=flat-square)](https://github.com/rahulkarda)

</div>

<details open="open">
<summary>Table of Contents</summary>

- [About](#about)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Support](#support)
- [Project assistance](#project-assistance)
- [Contributing](#contributing)
  - [Commiting Code](#commiting-code)
  - [Branch naming & pull requests](#branch-naming--pull-requests)
- [Authors & contributors](#authors--contributors)
- [Security](#security)
- [License](#license)
- [Domains](#domains)

</details>

---

<br/>

## About

In today's educational landscape, the need for an effective Learning Management System (LMS) is paramount. With the growing demand for online education and e-learning, institutions and organizations require an efficient platform that can manage, organize, and deliver educational content to learners effectively .Students often have difficulty keeping track of dense information - especially in an academic setting. To solve these issues, we decided to address these issues.

Together, we designed a prototype that will allow us to track classes, assignments, and resources automatically. The app will also enable students to connect easily on Discord when help is needed.

<br/>

### Built With

- [**Next.js**](https://nextjs.org/) [(Repo)](https://github.com/vercel/next.js)
- [**React.js**](https://reactjs.org/) [(Repo)](https://github.com/facebook/react/)
- [**Prisma**](https://www.prisma.io/) [(Repo)](https://github.com/prisma/prisma)
- [**NextAuth.js**](https://next-auth.js.org/) [(Repo)](https://github.com/nextauthjs/next-auth)
- [**Mantine**](https://mantine.dev/) [(Repo)](https://github.com/mantinedev/mantine/)
- [**Node.js**](https://nodejs.org/)
- [**MongoDB**](https://www.mongodb.com/)
- [**TailwindCSS**](https://tailwindcss.com/)
- [**Godaddy Domain Registry**](https://tech.study)

<br/>

## Getting Started

<br/>

### **Prerequisites**

This repo requires the use of [`pnpm`](https://pnpm.io/). To install, run the command:

```bash
npm -g install pnpm
```

or follow the instructions on [pnpm's installation page](https://pnpm.io/installation).



<br/>

### **Installation**

To install the required packages & dependencies:

```bash
pnpm install
```

<br/>

### **Environment Variables**

- This will require that you setup a MongoDB database. We recommend using MongoDB Atlas because there's a free option.
- You will also need access to our Discord Developer Portal. For this, you can reach out @GarlandKey or @JoeKarow.
- Do not try to run the server locally until you have completed the MongoDB and Discord setup.

Copy `.env.example` in the root directory and name it `.env`

```bash
cp .env.example .env
```

Follow the instructions listed in the newly created `.env`.

Once complete, you'll need to seed the database with test data. Do this as follows:

```bash
pnpm db:seed
pnpm db:devseed
```

<br/>

## Usage

To start the development live server:

```bash
pnpm dev
```

<br/>

## Roadmap

1. Minimum Viable Product
   - Account system
   - Welcome page
   - Classes page
   - Assignments page
2. Calendar page
3. Tasks page
4. Help Link system
5. Moderator Operation system

<br/>

## Support

Reach out to the maintainer at one of the following places:

- [GitHub Discussions](https://github.com/rahulkarda)
- Contact options listed on [this GitHub profile](https://github.com/rahulkarda)

<br/>

## Project assistance

If you want to say **thank you** or/and support active development of thinkBig:

- Add a [GitHub Star](https://github.com/rahulkarda) to the project.
- Tweet about the LearnTogether.
- Write interesting articles about the project on [Dev.to](https://dev.to/), [Hashnode](https://hashnode.com/), [Medium](https://medium.com/) or your personal blog.

Together, we can make thinkBig **better**!

<br/>

## Contributing

First off, thanks for taking the time to contribute! Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make will benefit everybody else and are **greatly appreciated**.

Please read [our contribution guidelines](docs/CONTRIBUTING.md), and thank you for being involved!

<br/>

### **Commiting Code**

This repo has a hook workflow to assist in the generation of [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/). When you wish to commit, please run the `git commit` command from the terminal and not the GUI. You will be prompted for information to build the commit. After you complete the prompts, the commit message will be opened in the designated editor in your `git` settings for you to preview before the code is committed.

If you don't want to constantly get stuck in `vi` hell, follow [these instructions](https://docs.github.com/en/get-started/getting-started-with-git/associating-text-editors-with-git) to change the default editor that `git` uses.

<br/>

### **Branch naming & pull requests**

This repo is set up to not allow any commits to be pushed directly to the `main` or `develop` branches.

Create a new branch using the format `YourUserName/very-short-description`.
When you're ready to submit a pull request, you will want to merge it in to `develop`. Ideally, this pull request will correspond with one or more [Issues](https://github.com/100Devs-ADHD/think-big/issues).

We will submit pull requests from `develop` to `main` when we have enough meaningful changes committed.

<br/>

## License

This project is licensed under the **GNU General Public License v3**.

See [LICENSE](LICENSE) for more information.

## Domains
1. wittylearners.study
2. learn2hack.us
3. learnwithwitty.club

