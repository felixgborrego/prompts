# promts

## Dev Laptop setup

```
Write a script to setup and install a new laptop.

 Add customization for the macOS Zsh terminal for developers to show git commit and branch status using the robbyrussell zsh theme.

 I want to install:
- brew
- iterm2 
- intellj CE
- pycharm
- sdkman,
- brew install protobuf
- using sdkman: install Scala, sbt, java 11, Maven
- python, conda, 
- minikube
- SourceTree, Visual Code, Docker, Lens, Authy, headlamp, rectangle, Google Drive, Teams, Slack
- Google Cloud CLI tools (and install the components: kubectl)
- dbeaver-community
- rust cargo (using rustup script)
- golang with brew (and configure GOPATH as $HOME/code/go and PATH with the brew installed version in zshrc)
- GitHub CLI, git lfs, Microsoft Git Credential Manager
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

Also, configure Macos with:
- Show hidden files
- Hide Dock
- Add launcher for Idea CE to the PATH
-  
```
