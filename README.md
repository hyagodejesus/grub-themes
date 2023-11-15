# grub-themes
Este repositório contém diversos temas personalizados para o Grub.

### ✔️ Instalação Manual
<details>
 <summary><b>Debian 💀 Ubuntu 💀 Arch</b></summary>
 
  #### 1️⃣ Faça o download do repositório [**Aqui**](https://github.com/hyagoshodan/Grub-themes/archive/refs/heads/main.zip).

  Agora extraia o arquivo zip.

  Extraia o arquivo pelo gerenciador de arquivos ou use o comando abaixo.
  ```fish
  unzip grub-themes-main.zip
  ```
  *O restante dos comandos são os mesmos para todos os estilos de tema.*

  #### 2️⃣ Copie o diretório do tema (Aqui estou usando a versão 'city1' como exemplo).
  ```fish
  sudo cp -r city1 /boot/grub/themes/
  ```
  #### 3️⃣ Faça as seguintes alterações no arquivo de configuração do Grub.

  ```fish
  sudo vim /etc/default/grub
  ```
  Encontre a linha `GRUB_THEME=` então faça a seguinte alteração `GRUB_THEME="/boot/grub/themes/city1/theme.txt"`

  Então salve o arquivo.

  #### 4️⃣ Finalmente, atualize o arquivo de configuração do Grub.
  ```fish
  sudo grub-mkconfig -o /boot/grub/grub.cfg
  ```
  Agora o tema já deve estar intalado, aproveite !!
</details>

<details>
 <summary><b>Fedora 💀 Redhat</b></summary>
 
  #### 1️⃣ Faça o download do repositório [**Aqui**](https://github.com/hyagoshodan/Grub-themes/archive/refs/heads/main.zip).

  Agora extraia o arquivo zip.

  Extraia o arquivo pelo gerenciador de arquivos ou use o comando abaixo.
  ```fish
  unzip grub-themes-main.zip
  ```
   *O restante dos comandos são os mesmos para todos os estilos de tema.*

  #### 2️⃣ Copie o diretório do tema (Aqui estou usando a versão 'city1' como exemplo).
  ```fish
  sudo cp -r city1 /boot/grub/themes/
  ```
  #### 3️⃣ Faça as alterações no arquivo de configuração do Grub.

  ```fish
  sudo vim /etc/default/grub
  ```
  Encontre a linha `GRUB_THEME=` então faça a seguinte alteração `GRUB_THEME="/boot/grub2/themes/city1/theme.txt"`
 
  Altere a linha `GRUB_TERMINAL_OUTPUT=console` para  `#GRUB_TERMINAL_OUTPUT=console`

  Então, salve o arquivo.

  #### 4️⃣ Finalmente, atualize o arquivo de configuração do Grub.
  ```fish
  sudo grub2-mkconfig -o /boot/grub2/grub.cfg
  ```
  Agora reinicie o seu computador e o tema do grub já deve estar instalado, aproveite !!
</details>


### ❌ Desinstalação
```fish
sudo rm -rf /boot/grub2/themes/city1
```

## 📸 Pré-visualição

|    |    |    |
|:-------:|:-------:|:---------:|
|![City 1](./temas/city1/background.png/)|![City 2](./temas/city2/background.png)|![City 3](./temas/city3/background.jpg)|
|**City 1**|**City 2**|**City 3**|
|![kali](./temas/kali/background.png)|![kali](./temas/gnu/background.png)| ![kali](./temas/root/background.png)
|**Kali**|**GNU**|**Root**|

