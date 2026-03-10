# IDEAS Lab Group Website

This repository contains the IDEAS Lab website built on Jekyll/al-folio, customized for a lab page.

## Local development via Docker (recommended)

```bash
docker compose pull
docker compose up
```

Site URL: `http://localhost:8080`

## Main pages

- `Publications` (`/publications/`)
  - Source page: `_pages/publications.md`
  - Bibliography file: `_bibliography/papers.bib`
- `Projects` (`/projects/`)
  - Source page: `_pages/projects.md`
  - Project entries: `_projects/*.md`
- `People` (`/people/`)
  - Source page: `_pages/profiles.md`
  - People data: `_data/people.yml`
  - Member photos: `assets/img/members/`
- `News` (`/news/`)
  - Source page: `_pages/news.md`
  - News entries: `_news/*.md`

## Notes

- Template modules that were removed from this site include blog, CV, teaching, books, repositories, and dropdown submenu pages.
- Examples of projects pages can be found in archive. 
- When adding to `papers.bib`, remember to add abbr field so the article can be tagged. If you'd like to include a preview image or gif, use the preview field and put the asset under `assets/img/publication_preview`