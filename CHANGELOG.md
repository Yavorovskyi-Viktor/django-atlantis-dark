# Change Log

## [1.0.8] 2024-11-27
### Changes

> Update RM Links

- 👉 [Django Atlantis Dark](https://app-generator.dev/product/atlantis-dark/django/) - `Product Page`
- 👉 [Django Atlantis Dark](https://app-generator.dev/docs/products/django/atlantis-dark/index.html) - `Complete Information` and Support Links
  - [Getting Started with Django](https://app-generator.dev/docs/technologies/django/index.html) - a `comprehensive tutorial`
  - `Configuration`: Install Dependencies, Prepare Environment, Setting up the Database 
  - `Start with Docker`
  - `Manual Build`
  - `Start the project`
  - `Deploy on Render`

## [1.0.7] 2023-10-24
### Changes

- Update Dependencies 
- Update README 

## [1.0.6] 2023-06-20
### Changes

- Added theme-based pattern

## [1.0.5] 2021-06-09
### Changes

- Built with [Atlantis Dark Generator](https://appseed.us/generator/atlantis-dark/)
  - Timestamp: `2022-06-09 12:04`

## [1.0.4] 2022-01-16
### Changes

- Bump Django Codebase to [v2stable.0.1](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
- Dependencies update (all packages) 
  - Django==4.0.1
- Settings update for Django 4.x
  - `New Parameter`: CSRF_TRUSTED_ORIGINS
    - [Origin header checking isn`t performed in older versions](https://docs.djangoproject.com/en/4.0/ref/settings/#csrf-trusted-origins)  

## [1.0.3] 2021-10-12 
### Improvements

- Bump Django Codebase to [v2.0.4](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
- Codebase update
  - `assets` & `templates` moved to `apps` folder
  - `apps/base` renamed to `apps/home`

## [1.0.2] 2021-09-12
### Improvements & Fixes

- Bump Django Codebase to [v2.0.2](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
  - Dependencies update (all packages)
    - Use Django==3.2.6 (latest stable version)
  - Better Code formatting
  - Improved Files organization
  - Optimize imports
  - Docker Scripts Update 
-Tooling:
  - SASS compilation via Gulp  
- Fixes: 
  - Patch 500 Error when authenticated users access `admin` path (no slash at the end)
  - Patch [#16](https://github.com/app-generator/boilerplate-code-django-dashboard/issues/16): Minor issue in Docker 

## [1.0.1] 2021-01-21

- Bump UI: [Jinja Atlantis Dark](https://github.com/app-generator/jinja-atlantis-dark/releases) 1.0.1
- [Atlantis Lite](https://github.com/themekita/Atlantis-Lite): 2021-01-05 Snapshot
- Codebase: [Django Dashboard](https://github.com/app-generator/boilerplate-code-django-dashboard/releases) v1.0.4

## [1.0.0] 2020-02-07
### Initial Release
