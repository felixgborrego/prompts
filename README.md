# promts

## Dev Laptop setup

### Step 1

```
Write a script to setup and install a new laptop.

 Add customization for the macOS Zsh terminal for developers to show git commit and branch status using the robbyrussell zsh theme.

 I want to install:
- brew
- iterm2 
- intellj CE
- pycharm
- miro
- sdkman,
- Google Cloud CLI tools (and install the components: kubectl)
- SourceTree, Visual Code, Docker, Lens, Authy, headlamp, rectangle, Google Drive, Teams, Slack
- minikube
- teleport and configure KUBECONFIG as 'export KUBECONFIG=${HOME?}/.kube/teleport-kubeconfig.yaml'
- kube-ps1 with brew

Also, configure Macos with:
- Show hidden files
- Hide Dock
- Add launcher for Idea CE to the PATH
- Create an alias k for kubectl
- configure the PROMPT as:
   NEWLINE=$'\n'
   PROMPT="%(?:%{$fg_bold[green]%}➜ :%{$fg_bold[red]%}➜ ) %{$fg[cyan]%}%~%{$reset_color%}"
   PROMPT+=' $(kube_ps1) $(git_prompt_info) $NEWLINE%(!.#.$) '

```

### Step 2
```
- using sdkman: install Scala, sbt, java 11.0.20-tem, Maven
- python, conda, 
- using brew, install:  node, pulumi, protobuf, grpcurl, jq, bloomrpc, bufbuild/buf/buf
- install yarn using npm
- dbeaver-community
- rust cargo (using rustup script)
- golang with brew (and configure GOPATH as de defaultas $HOME/go and the GOPATH/bin to the PATH)
- GitHub CLI, git-lfs, git-credential-manager-core
- wget
Add a comment explaining what the software is for and divided in functions.
The script must report the installation success/failure of each application at the end

for go, install the following modules:
- go install google.golang.org/protobuf/cmd/protoc-gen-go@latest
- go install github.com/gogo/protobuf/protoc-gen-gofast@latest
- go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@latest
- go install github.com/infobloxopen/protoc-gen-gorm@v1.0.1
- go install github.com/vektra/mockery/v2@latest
and create the folder:
mkdir -p $GOPATH/src/github.com

- Configure gitglobal with:
# To access private repositories use ssh https://go.dev/doc/faq#git_https	
[url "ssh://git@github.com/"]
	insteadOf = https://github.com/
```
