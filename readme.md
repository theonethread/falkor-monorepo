# **Falkor Monorepo**

Monorepo for easier Falkor Framework development.

## **Workspaces**

The workspaces used in this project build upon each other, so the order in [`package.json`](package.json "Open") matters. All packages in the repo are built in a way that they can be cloned and developed independently, but for the organization to save space and bandwidth, this approach is preferred. The packages included are the following:

* Documentation (`/doc`)
    * [`@falkor/falkor-knowledge-base`](https://github.com/theonethread/falkor-knowledge-base/#readme "Open")

* Shared modules ([`/shared_modules/*`](/shared_modules "Open"))
    * [`@falkor/falkor-cspell-config`](https://github.com/theonethread/falkor-cspell-config/#readme "Open")
    * [`@falkor/falkor-prettier-config`](https://github.com/theonethread/falkor-prettier-config/#readme "Open")
    * [`@falkor/falkor-eslint-config`](https://github.com/theonethread/falkor-eslint-config/#readme "Open")
    * [`@falkor/falkor-jest-config`](https://github.com/theonethread/falkor-jest-config/#readme "Open")
    * [`@falkor/falkor-jscc-webpack-plugin`](https://github.com/theonethread/falkor-jscc-webpack-plugin/#readme "Open")
    * [`@falkor/falkor-bundler`](https://github.com/theonethread/falkor-bundler/#readme "Open")
    * [`@falkor/falkor-library`](https://github.com/theonethread/falkor-library/#readme "Open")
    * [`@falkor/falkor-commander`](https://github.com/theonethread/falkor-commander/#readme "Open")
* Projects ([`/projects/*`](/projects "Open"))
    * [`@falkor/falkor-auth-server`](https://github.com/theonethread/falkor-auth-server/#readme "Open")
    * [`@falkor/falkor-plugin-example`](https://github.com/theonethread/falkor-plugin-example/#readme "Open")

## **Further Development**

### **Security**

The project uses [CodeQL](https://codeql.github.com "Visit") and [Snyk](https://snyk.io "Visit") to ensure standard security.

> _The **Falkor Framework** supports a healthy and ubiquitous Internet Immune System enabled by security research, reporting, and disclosure. Check out our [Vulnerability Disclosure Policy](https://github.com/theonethread/falkor-monorepo/security/policy "Open") - based on [disclose.io](https://disclose.io "Visit")'s best practices._

### **Free and Open Source**

The latest sources can always be found on [GitHub](https://github.com/theonethread/falkor-monorepo "Visit").

#### **Getting Involved**

We believe - and we hope you do too - that learning how to code, how to think, and how to contribute to free- and open source software can empower the next generation of coders and creators. We **value** first time contributors just the same as rock stars of the OSS world, so if you're interested in getting involved, just head over to our [Contribution Guidelines](https://github.com/theonethread/.github/blob/master/.github/contributing.md "Open") for a quick heads-up!

#### **License**

[MIT](https://github.com/theonethread/falkor-monorepo/blob/master/license.txt "Open")

##

---

_©2020-2023 Barnabas Bucsy - All rights reserved._
