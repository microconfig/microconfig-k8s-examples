# Example of config repo layout that can be built by Microconfig

To build configs:
1) Clone this repo.
2) Download the last microconfig.jar(or compiled binary for your OS) from https://github.com/microconfig/microconfig/releases
4) Execute the build config command.

```
git clone https://github.com/microconfig/microconfig-k8s-examples.git
mcVersion=v4.1.4
curl -SL  https://github.com/microconfig/microconfig/releases/download/${mcVersion}/microconfig.jar --output microconfig.jar
java -jar microconfig.jar -r microconfig-k8s-examples -e prod
```
