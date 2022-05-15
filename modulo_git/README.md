# Instalação e configuração do git e github


1. instalação do git 
   1. instalação do windows 
       - **Download git** \
         [Site official git](https://git-scm.com)
   1. instalaçãod do linux
      - **Debian, ubuntu, linuxminit, popos**
         ```
         sudo apt-get install git -y
         ```
2. criação de conta no github
   1. criação da chave ssh
      ```
      ssh-keygen -t ed25519 -C "seu email"
      ```
   1. criar conta no github \
      [site do para cadastro do github](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)
   1. inserir a chave ssh no github\
      ```
      Settings -> ssh and gpg keys -> new ssh key
      ```
   1. configurar o ssh da maquina
   ```
   eval $(ssh-agent)
   ```
3. criação de repositorio

4. vincular e clonar projetos
