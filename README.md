## INSTALAÇÃO DO GIT E CRIAÇÃO DE CHAVE SSH.

### No terminal linux digite os seguintes códigos:

---

```
mkdir .ssh
```

```
sudo apt-get install git
```

```
sudo add-apt-repository ppa:git-core/ppa
```

```
sudo apt update
```

```
sudo apt install git
```

```
sudo apt-get install gitk (interface gráfica para observar os commits)
```

---

## GERANDO CHAVE SSH

```
cd~  (volta para a pasta home)
```

```
ssh-keygen -o -t rsa -C "seuemaildogithub@seuprovedor.com"
```

### Precionar somente enter 2x para deixar as demais validações vazias.

```
cat ~/.ssh/id_rsa.pub
```

### Copiar a chave e colocar no perfil do github.
