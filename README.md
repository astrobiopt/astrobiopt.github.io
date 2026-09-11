# AstroBioLusitanos — Site Oficial

Este repositório contém o código do site dos **AstroBioLusitanos (ABL)**, uma equipa de jovens cientistas portugueses dedicados à divulgação da astrobiologia e das ciências do espaço em Portugal.

🔗 Instagram: [@astrobiopt](https://www.instagram.com/astrobiopt)
📧 Contacto: astrobiolusitanos@gmail.com

---

## O que tem o site

- **Página inicial** — animação de entrada com o logótipo, banner com imagens do "passado" e "futuro" da astrobiologia, secção "Quem somos", e um mural de últimas novidades com destaque + lista em scroll automático.
- **Equipa** (`team.html`) — apresentação dos membros da ABL, por área científica (astronomia, biologia, microbiologia, física, engenharia, geologia).
- **Onde já estivemos** (`onde-estivemos.html`) — mapa interativo de Portugal por distrito, com alternância entre escolas e universidades/eventos, ligando a uma página de detalhe por cada visita.
- **Entrevistas** (`entrevistas.html`) — série "AstroBioEstrela", com conversas com quem faz ciência espacial em Portugal e no mundo.
- **Workshops** (`services.html`) — apresentações e workshops que a equipa oferece a escolas e universidades.
- **Contactos** (`contactos.html`) — formulário de contacto e pedido de visita a escolas.

## Estrutura de pastas

```
/
├── index.html                  # página inicial
├── team.html                   # equipa
├── entrevistas.html             # lista de entrevistas
├── onde-estivemos.html          # mapa interativo
├── services.html                # workshops
├── contactos.html
├── artigos.html
├── merch.html
│
├── entrevistas/                  # páginas de detalhe de cada entrevista
├── workshops/                    # páginas de detalhe de cada workshop
├── onde_estivemos/
│   ├── escolas/                  # páginas de detalhe de cada escola visitada
│   └── universidades/            # páginas de detalhe de universidades e eventos
│
├── css/                          # Bootstrap + estilos do template
├── js/                           # jQuery, Bootstrap JS e scripts do template
├── fonts/                        # tipos de letra (Font Awesome / Glyphicons)
└── images/                       # logótipo, fotos de equipa, entrevistas, visitas, etc.
```

## Pré-visualizar localmente

Não é necessário nenhum servidor ou processo de build — é um site estático. Basta abrir `index.html` diretamente num browser, ou correr um servidor local simples a partir da pasta raiz, por exemplo:

```bash
python3 -m http.server 8000
```

e visitar `http://localhost:8000`.

## Créditos

- **Template base:** [TechKing](http://webthemez.com), por WebThemez — construído sobre o [Bootstrap](http://getbootstrap.com).
- Ver `readme.txt` para os termos de licença completos do template.

---

*Site mantido pela equipa AstroBioLusitanos. Para sugestões, correções ou informação nova a adicionar (visitas, entrevistas, membros da equipa), contactar a equipa pelos canais acima.*
