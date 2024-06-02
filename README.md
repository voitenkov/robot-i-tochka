# Робот - и точка: документация!!!

https://squidfunk.github.io/mkdocs-material/creating-your-site/
docker run --rm -it -v "${PWD}:/docs" squidfunk/mkdocs-material new .

docker run --rm -it -p 8000:8000 -v "${PWD}:/docs" squidfunk/mkdocs-material

