# cohen-r.github.io

Personal site for Rachel Cohen, built with Jekyll on GitHub Pages.

## Where to edit things

| To change…                            | Edit                          |
|---------------------------------------|-------------------------------|
| Email, Scholar, ORCID, CV PDF link    | `_config.yml`                 |
| Home page text, photos, figures       | `index.html`                  |
| Publications (also used on the CV)    | `_data/publications.yml`      |
| CV page                               | `cv.html`                     |
| CV PDF download                       | replace `files/Cohen_CV.pdf`  |
| Courses taught                        | `_data/courses.yml`           |
| Student evaluations                   | `_data/evaluations.yml` and `files/evaluations/` |
| Teaching notebooks list               | `_data/notebooks.yml`         |
| Teaching development roles            | `_data/pedagogy.yml`          |
| Colors and fonts                      | `assets/css/style.css`        |
| Photos and figures                    | `assets/img/`                 |

## Updating a rendered notebook

The "Read the notebook" pages in `teaching/notebooks/` are static copies, so
they don't change when you edit a notebook. After editing, re-render with:

    pip install nbconvert
    jupyter nbconvert --to html --template lab "Lotka-volterra.ipynb" --output lotka-volterra
    
and replace the matching file in `teaching/notebooks/`. (The current copies
also have a green "Back to Teaching / Run in Binder" bar added at the top;
a re-rendered file won't have it unless you add it back.)

Tip: in notebook Markdown cells, close every `<div>` with `</div>`. Jupyter
forgives a missing close tag, but GitHub and nbviewer don't, and the rest
of the notebook disappears into the box.
