# Agent Guidelines for tibudiyanto.github.io

## Build Commands
- `make html` - Generate static site
- `make clean` - Remove generated files
- `make serve` - Serve site at localhost:8000
- `make devserver` - Serve with auto-regeneration
- `make publish` - Build for production
- `invoke build` - Alternative build command
- `invoke livereload` - Auto-reload development server

## Testing
- No specific test framework configured
- Manual testing via `make serve` or `invoke serve`

## Code Style
- Python 3.10+ (see devbox.json)
- Pelican static site generator
- Content in Markdown format in `content/` directory
- Templates use Jinja2 syntax in `theme/templates/`
- Follow PEP 8 for Python code
- Use double quotes for strings in Python files
- Configuration in `pelicanconf.py` and `publishconf.py`

## File Structure
- `content/blog/` - Blog posts in Markdown
- `content/til/` - Today I Learned posts
- `theme/` - Custom Pelican theme
- `docs/` - Generated output (GitHub Pages)
- `output/` - Alternative output directory