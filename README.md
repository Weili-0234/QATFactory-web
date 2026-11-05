# QATFactory project page

Project page for [QATFactory: A Versatile, Deployment-Aligned Framework for Quantization-aware Training and
Distillation of LLMs](https://arxiv.org/abs/2609.39223).

- Page: https://weilixu.com/QATFactory-web/ (source in `docs/`, served by GitHub Pages)
- Code: https://github.com/QATFactory/QATFactory
- Models and data: https://huggingface.co/qatfactory

## Layout

| Path | Content |
| --- | --- |
| `docs/index.html` | The page: one static file with its CSS and JavaScript inline; Google Fonts load from a CDN. No build step. |
| `docs/fig/` | Paper figures rendered to PNG from the paper's PDF figures (`pdftoppm -png -r 220`). |

## View the page locally

```
python3 -m http.server -d docs 8000    # then open http://localhost:8000
```
