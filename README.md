The Markdown Resume
===================

### Instructions
```bash
git clone https://github.com/mattocci27/markdown_CV
cd markdown_CV
vim CV.md   # insert your own resume info
make
```

### Running Dockerized
```bash
git clone https://github.com/mattocci27/markdown_CV
cd markdown_CV
vim CV.md   # insert your own resume info
sudo docker-compose up -d

sudo docker-compose up --build
```

### Requirements

 * ConTeXt
 * pandoc

#### Debian
```bash
sudo apt install pandoc context
```

#### Fedora
```bash
sudo dnf install pandoc texlive-collection-context
```

sudo docker run -it --rm -v $(pwd):/home/app ubuntu /bin/bash
