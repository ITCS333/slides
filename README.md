# ITCS333 Slides

## Requirements:
```bash
sudo dnf install texlive-*
sudo dnf install pandoc
sudo dnf install ImageMagick
```

## Generate PDFs:
```bash
pandoc --slide-level 2 -t beamer ch1.md -o pdf/ch1.pdf
```
