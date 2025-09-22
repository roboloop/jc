# jc

Just commit — a simple commit message generator powered by AI.

Feel free to write your own instructions for your projects.

## Features

- [x] Generate a commit message based on a custom instruction file 
- [ ] Instal

## Requirements

- OS Linux/MacOS
- [git](https://git-scm.com/)
- [curl](https://curl.se/)
- [jq](https://github.com/jqlang/jq)

## Setup

1. Install in `$HOME/.jc`
    
   ```shell
   curl -sL https://raw.githubusercontent.com/roboloop/jc/refs/heads/main/install.sh | bash
   ```

2. Make the program globally accessible by adding to the corresponding command to the shell-config

   ```shell
   export PATH="$HOME/.jc:$PATH"`
   ```
   
3. Set up the instruction file. There are two ways to do this: 

   1. Global one: `$HOME/.jc/.jcrc`

   2. Git project: `git-project/.jcrc`

      > You can exclude `.jcrc` file in `.git/info/exclude`

   3. Environment variables

## Usage

Just run `jc` in your terminal.

```shell
jc
```

## Inspired by

- [aicommits](https://github.com/Nutlope/aicommits)
- [opencommit](https://github.com/di-sukharev/opencommit)
