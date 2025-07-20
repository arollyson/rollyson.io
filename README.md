 ```
██╗  ██╗ ██████╗ ███╗   ███╗███████╗    ██████╗  █████╗  ██████╗ ███████╗
██║  ██║██╔═══██╗████╗ ████║██╔════╝    ██╔══██╗██╔══██╗██╔════╝ ██╔════╝
███████║██║   ██║██╔████╔██║█████╗      ██████╔╝███████║██║  ███╗█████╗  
██╔══██║██║   ██║██║╚██╔╝██║██╔══╝      ██╔═══╝ ██╔══██║██║   ██║██╔══╝  
██║  ██║╚██████╔╝██║ ╚═╝ ██║███████╗    ██║     ██║  ██║╚██████╔╝███████╗
╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝    ╚═╝     ╚═╝  ╚═╝ ╚═════╝ ╚══════╝
```

# Alek Rollyson - Personal Website

## 🚀 Quick Start

### Prerequisites
- Docker and Docker Compose
- Or Ruby with Jekyll installed

### Running Locally

**Option 1: Using Docker (Recommended)**
```bash
docker compose up
```
Then visit `http://localhost:4000`

**Option 2: Using Ruby/Jekyll directly**
```bash
cd home
bundle install
bundle exec jekyll serve
```

## 🏗️ Project Structure

```
rollyson.io/
├── home/                 # Jekyll site source
│   ├── _config.yml      # Site configuration
│   ├── index.md         # Homepage content
│   ├── _data/           # Site data files
│   └── _site/           # Generated site (gitignored)
├── docker-compose.yaml  # Docker setup for development
└── README.md           # This file
```

## 🎨 Theme

This site uses the [hacked-jekyll](https://github.com/piazzai/hacked-jekyll) theme

## 🔧 Development

- **Site URL**: https://rollyson.io
- **Local Development**: http://localhost:4000
- **Build Tool**: Jekyll
- **Theme**: hacked-jekyll