# Johnny Chang's Resume

[![Release](https://img.shields.io/github/release/Johnny-Chang-ZZZ/resume.svg?style=for-the-badge)](https://github.com/Johnny-Chang-ZZZ/resume/releases/latest)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=for-the-badge)](./LICENSE)
[![Build status](https://img.shields.io/github/workflow/status/Johnny-Chang-ZZZ/resume/general/main?style=for-the-badge)](https://github.com/Johnny-Chang-ZZZ/resume/actions?workflow=general)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?style=for-the-badge)](https://github.com/semantic-release/semantic-release)

Forked from [kirintwn/resume](https://github.com/kirintwn/resume). My resume written in LaTeX based on [Awesome-CV](https://github.com/posquit0/Awesome-CV) with complete CI/CD pipline. Fully automated testing, building & release process is powered by GitHub Actions & [semantic-release](https://github.com/semantic-release/semantic-release). The output pdf can be found in the [releases section](https://github.com/Johnny-Chang-ZZZ/resume/releases/latest), or the preview is available [here](https://johnny-chang-zzz.github.io/resume/resume.pdf) with GitHub Pages.

## Download: [resume.pdf](https://johnny-chang-zzz.github.io/resume/resume.pdf)

## Local Development

### Setup

The following tools need to be installed on your system in advance:

- `git`: `>=2`
- `docker`: `>=18.09`
- `earthly`: `>=0.6.8 <7`

First clone the repository:

```shell
git clone git@github.com:Johnny-Chang-ZZZ/resume.git
```

### Test & Build Locally

- test: `earthly +test`
- build: `earthly +build`
- run test & build: `earthly +all`

## Credits

The list of some third party components used in this project, with due credits to their authors and license terms. More details can be found in their README documentations.

- [posquit0/Awesome-CV](https://github.com/posquit0/Awesome-CV)
- [xu-cheng/latex-action](https://github.com/xu-cheng/latex-action)
- [earthly/earthly](https://github.com/earthly/earthly)
