# Grub-themes
Este repositório contém diversos temas personalizados para o Grub.

### ✔️ Instalação Manual
<details>
 <summary><b>Debian 💀 Ubuntu 💀 Arch</b></summary>
 
  #### 1️⃣ Faça o seu download favorito [**Aqui**]().

  Agora extraia o arquivo zip.

  Extraia manualmente ou use o comando abaixo. (Aqui estou usando a versão 'corinthians1' como exemplo)
  ```fish
  unzip corinthians1.zip
  ```
  *O restante dos comandos são os mesmos para todos os estilos de tema.*

  #### 2️⃣ Copie o diretório do tema.
  ```fish
  sudo cp -r corinthians1 /boot/grub/themes/
  ```
  #### 3️⃣ Faça as seguintes alterações no arquivo de configuração do Grub.

  ```fish
  sudo vim /etc/default/grub
  ```
  Encontre a linha `GRUB_THEME=` então faça a seguinte alteração `GRUB_THEME="/boot/grub/themes/corinthians1/theme.txt"`

  Então salve o arquivo.

  #### 4️⃣ Finalmente, atualize o arquivo de configuração do Grub.
  ```fish
  sudo grub-mkconfig -o /boot/grub/grub.cfg
  ```
  Agora o tema já deve estar intalado, aproveite !!
</details>

<details>
 <summary><b>Fedora 💀 Redhat</b></summary>
 
  #### 1️⃣ Faça o seu download favorito [**Aqui**]().

  Agora extraia o arquivo zip.

  Extraia manualmente ou use o comando abaixo. (Aqui estou usando a versão 'corinthians1' como exemplo)
  ```fish
  unzip corinthians1.zip
  ```
   *O restante dos comandos são os mesmos para todos os estilos de tema.*

  #### 2️⃣ Copie o diretório do tema.
  ```fish
  sudo cp -r corinthians1 /boot/grub/themes/
  ```
  #### 3️⃣ Make changes to the GRUB config file.

  ```fish
  sudo vim /etc/default/grub
  ```
  Encontre a linha `GRUB_THEME=` então faça a seguinte alteração `GRUB_THEME="/boot/grub2/themes/corinthians1/theme.txt"`
 
  Altere a linha `GRUB_TERMINAL_OUTPUT=console` para  `#GRUB_TERMINAL_OUTPUT=console`

  Then save the file.

  #### 4️⃣ Finalmente, atualize o arquivo de configuração do Grub.
  ```fish
  sudo grub2-mkconfig -o /boot/grub2/grub.cfg
  ```
  Agora reinicie o seu computador e o tema do grub já deve estar instalado, aproveite !!
</details>


### ❌ Desinstalação
```fish
sudo rm -rf /boot/grub2/themes/corinthians1
```

## 📸 Pré-visualição

|    |    |    |
|:-------:|:-------:|:---------:|
|![Corinthians 1](./temas/corinthians1/background.png/)|![Corinthians 2](./temas/corinthians2/background.png)|![Corinthians 3](./temas/corinthians3/background.png)|
|**Corinthians 1**|**Corinthians 2**|**Corinthians 3**|
|![Palmeiras 1](./temas/palmeiras1/background.png)|
|**Palmeiras 1**|