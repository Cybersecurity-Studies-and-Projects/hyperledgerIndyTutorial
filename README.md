# hyperledgerIndyTutorial

* Para preparar o ambiente de desenvolvimento voltado para .Net são necessários alguns
pré-requisitos.

<b>Visual Studio Code</b>
* https://code.visualstudio.com/
    * Após a sua instalação adicione as extensões C# e Nuget package manager
* .Net Core na versão 2.2.

<b>Instalando o Indy-SDK.</b>

```shell
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys
68DB5E88
sudo add-apt-repository "deb https://repo.sovrin.org/sdk/deb
xenial stable"
sudo apt-get update
sudo apt-get install -y libindy
```