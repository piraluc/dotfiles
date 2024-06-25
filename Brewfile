# This file describes the desired state of brew installed apps if using the followimg commands::
# alias brew-update='brew update; brew bundle check --global || ( brew bundle --global; brew bundle --cleanup --global); brew upgrade; brew cleanup'

cask_args appdir: '/Applications'

# Taps
tap 'homebrew/bundle'           # -- Bundler for non-Ruby dependencies from Homebrew, Homebrew Cask, Mac App Store and Whalebrew
tap 'homebrew/services'         # -- Manage background services with macOS' launchctl daemon manager.

# Virtualisation
cask 'docker'
#cask 'virtualbox
#cask 'podman-desktop'

# AWS
tap 'versent/homebrew-taps'
brew 'saml2aws'                 # -- enables you to login and retrieve AWS temporary credentials using with ADFS or PingFederate Identity Providers
brew 'awscli'                   # -- Official Amazon AWS command-line interface
cask 'session-manager-plugin'   # -- Plugin for AWS CLI to start and end sessions that connect to managed instances
#tap 'weaveworks/tap'
#brew 'weaveworks/tap/eksctl'   # -- a CLI tool for creating clusters on EKS
cask 'aws-vault'                # -- Tool to securely store and access AWS credentials in a development environment
#brew 'awsume'                  # -- Utility for easily assuming AWS IAM roles from the command-line
#brew 'aws-iam-authenticator'   # -- Using AWS EKS with kubectl

# Azure
# brew 'azure/draft/draft'
# brew 'azure-cli'

# GCP
# cask 'google-cloud-sdk'

# Terraform
brew 'tfenv', link: true        # -- Terraform version manager
brew 'tflint'                   # -- Linter for Terraform files
brew 'terraform-docs'           # -- Tool to generate documentation from Terraform modules
# terragrunt installed by tgenv
tap 'alextodicescu/tgenv'
brew 'tgenv', link: true        # -- Terragrunt version manager
brew 'tfsec'                    # -- Static analysis security scanner for your terraform code
brew 'terrascan'                # -- Detect compliance and security violations across Infrastructure as Code

brew 'pulumi'

# Kubernetes
brew 'stern'                    # -- Tail multiple Kubernetes pods & their containers
brew 'asdf'
brew 'kubectx'                  # -- Tool that can switch between kubectl contexts easily and create aliases
brew 'krew'                     # -- Package manager for kubectl plugins
brew 'kube-ps1'                 # -- Kubernetes prompt info for bash and zsh
tap 'derailed/k9s'
brew 'derailed/k9s/k9s'         # -- provides a terminal UI to interact with your Kubernetes clusters
brew 'kubeconform'
# brew 'minikube'               # -- Run a Kubernetes cluster locally

# Operator SDK
brew 'operator-sdk'             # -- SDK for building Kubernetes applications
brew 'derailed/popeye/popeye'   # -- A Kubernetes Cluster Sanitizer

# Helm
brew 'helm'                     # -- Kubernetes package manager
brew 'helmfile'                 # -- Deploy Kubernetes Helm Charts
tap 'helm/tap'
brew 'chart-releaser'           # -- Helps Turn GitHub Repositories into Helm Chart Repositories

# Kafka
brew 'kcat'                     # -- Generic command-line non-JVM Apache Kafka producer and consumer

# AI
brew 'ollama'

# Fonts
tap 'homebrew/cask-fonts'
brew 'svn'                      # -- Required by font-source-*-pro
brew 'highlight'                # -- Convert source code to formatted text with syntax highlighting
cask 'font-source-code-pro'     # -- Open Source Font
cask 'font-source-sans-3'       # -- Open Source Font
cask 'font-fantasque-sans-mono'
cask 'font-3270-nerd-font'      # -- I love nerd fonts
cask 'font-hack-nerd-font'      # -- I love nerd fonts
cask 'font-roboto-mono-for-powerline' # -- Monospace additions to Googles Roboto

# git
brew 'git'                      # -- Distributed revision control system --> Better use macOS git
#brew 'gitup'                   # -- Git interface focused on visual interaction
#brew 'git-secret'              # -- Prevents you from committing sensitive information to a git repo
#brew 'pre-commit'              # -- Framework for managing multi-language pre-commit hooks
brew 'git-crypt'                # -- Enable transparent encryption/decryption of files in a git repo
brew 'git-lfs'                  # -- Git extension for versioning large files

# GitHub
brew 'gh'                       # -- GitHub’s official command line tool
#brew 'gitversion'               # -- semantic versioning
brew 'git-credential-manager'   # -- Stores Git credentials
cask 'github'                   # -- Desktop client for GitHub repositories
cask 'gitkraken'                # -- Git client focusing on productivity
brew 'act'                      # -- Run your GitHub Actions locally

# Editor & Terminal tools
#cask 'alacritty'               # -- Cross-platform, GPU-accelerated terminal emulator
#brew 'ripgrep'                  # -- a line-oriented search tool that recursively searches your current directory for a regex pattern.
#brew 'tmux'                     # -- Terminal multiplexer
#cask 'obsidian'                 # -- Knowledge base that works on top of a local folder of plain text Markdown files
brew 'jq'                       # -- command-line JSON processor
brew 'yq'                       # -- Process YAML documents from the CLI
brew 'yamllint'                 # -- Linter for YAML files
# tap 'starkandwayne/cf'        # -- BOSH / Cloud Foundry / Kubernetes utilities
# brew 'spruce'                 # -- a general purpose YAML & JSON merging tool
brew 'telnet'
cask 'postman'                  # -- Collaboration platform for API development
cask 'bruno'
cask 'mactex-no-gui'            # -- Full TeX Live distribution without GUI applications, use with VScode extension "Latex Workshop"
cask 'tex-live-utility'         # -- Graphical user interface for TeX Live Manager
cask 'bibdesk'                  # -- Edit and manage bibliographies
cask 'latexit'                  # -- Graphical interface for LaTeX
cask 'texshop'                  # -- Tex previewer
cask 'iterm2'                   # -- Terminal emulator as alternative to Apple's Terminal app
cask 'microsoft-remote-desktop' # -- Remote desktop client
brew 'awk'

# IDEs
cask 'visual-studio-code'
cask 'intellij-idea'
cask 'webstorm'
cask 'datagrip'
cask 'mps'                      # -- JetBrains MPS - Create your own domain-specific language
cask 'appcode'
cask 'rider'
#cask 'staruml@3.2.2'           # -- Need to figure out how to stay with version 3.2.2
brew 'jupyterlab'
cask 'lens'                     # -- Kubernetes IDE
brew 'skaffold', link: true     # -- cli tool that facilitates continuous development for Kubernetes applications.
cask 'unity-hub'

# Postgres
brew 'libpq'
cask 'pgadmin4'

# Shell
brew 'bash'                     # -- install bash version > 4 (macos provides version 3)
brew 'fzf'                     # -- Command-line fuzzy finder written in Go
#brew 'direnv'                  # -- Load/unload environment variables based on $PWD
#brew 'shellcheck'              # -- Static analysis and lint tool, for (ba)sh scripts
#brew 'shfmt'                   # -- Autoformat shell script source code
#brew "gnu-sed"                 # -- GNU `sed`
brew 'zsh'                      # -- Z shell
brew 'zsh-completions'          # -- Additional completion definitions for zsh

# Node.js
brew 'nvm'                      # -- Manage multiple Node.js versions
brew 'yarn'                

# Build tools
brew 'cmake'

# Go
brew 'golang'

# Python
brew 'python3'

# Java
brew 'openjdk'                  # -- Development kit for the Java programming language
brew 'kotlin'
brew 'micronaut'

# .NET
tap 'isen-ng/dotnet-sdk-versions'
cask 'dotnet-sdk7-0-400'
cask 'dotnet-sdk8-0-100'

# swift
brew 'swiftlint'
cask 'sf-symbols'

# Angular
brew 'angular-cli'

# miscellaneous tools
#brew 'dialog'                  # -- Script-driven curses widgets (application and library)
#brew 'pandoc'                  # -- a universal document converter
#brew 'watch'                   # -- procps
#brew 'mosh'                    # -- mobile shell / Remote terminal application
#brew 'nmap'                    # -- utility for network discovery and security auditing
#brew 'coreutils'               # -- GNU core utilities
#brew 'tree'                    # -- recursive directory listing command
#brew 'mtr'                     # -- improved traceroute
#brew 'keychain'                # -- helps you to manage SSH and GPG keys in a convenient and secure manner
#cask 'gpg-suite'
brew 'openssh'
brew 'pinentry-mac'
brew 'wget'                     # -- retrieves content from web servers
##brew 'miniupnpc'              # -- enabling applications to access the services provided by an UPnP "Internet Gateway Device"
brew 'gnupg'                    # -- GNU Pretty Good Privacy (PGP) package
#brew 'pinentry-mac'            # -- Pinentry for GPG on Mac
#cask 'flux'                    # -- Adaptive brightness for external displays
brew 'hugo'
brew 'ffmpeg'

# more messengers ;)
cask 'slack'
cask 'telegram'
cask 'signal'
cask 'whatsapp'
cask 'messenger'

# miscellaneous apps
cask 'dropbox'                  # -- Client for the Dropbox cloud storage service
#cask 'alfred'                  # -- Application launcher and productivity software
#cask 'caffeine'                # -- Utility that prevents the system from going to sleep
#cask 'hazel'                   # -- Automated organization
#cask 'calibre'                 # -- E-books management software
#cask 'grandperspective'        # -- Graphically shows disk usage within a file system
#cask 'atext'                   # -- Tool to replace abbreviations while typing
#cask 'openconnect-gui'         # -- Graphical OpenConnect client
#cask '1password-cli'           # -- Command-line helper for the 1Password password manager
cask 'drawio'                  # -- free online diagram software
cask 'spotify'
cask '1password'
cask 'keepassxc'
cask 'miro'
cask 'microsoft-office'
cask 'adobe-acrobat-reader'
cask 'discord'
cask 'zoom'
cask 'webex'
brew 'ykman'
cask 'steam'
cask 'steelseries-gg'
cask 'balenaetcher'             # -- Tool to flash OS images to SD cards & USB drives
cask 'gather'                  # -- Virtual video-calling space
#cask 'blender'                 # -- 3D creation suite
brew 'ykman'
cask 'obs'
cask 'google-chrome'
cask 'deepl'
cask 'raspberry-pi-imager'
cask 'vlc'
cask 'nvidia-geforce-now'
cask 'background-music'
cask 'amazon-chime'