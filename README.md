# @rappstack/dev

This is the development repo for the rappstack (reactive app stack). See the [rappstack page](https://github.com/rappstack) for more info. Each library is a submodule targeted to a specific purpose (domain, ui, or both), environment (browser, server, or both) & the specific domain. These libraries are meant to be interoperate with each other. Application logic, UI, database migrations, & database access are included.

## Why no npm packages?

@rappstack/* packages are currently used as git submodules in a bun monorepo. This is to get some apps off the ground while working through some api churn. Git submodules make this process of app + library development faster. See the [rappstack page](https://github.com/rappstack) for more details.
