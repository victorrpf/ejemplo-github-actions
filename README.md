# Ejemplo de GitHub Actions (EDD-UD3.3)

Repositorio de ejemplo para clase:

- `.github/workflows/github-actions-demo.yml`: el workflow del inicio rápido de GitHub, con comentarios.
- `.github/workflows/python-app.yml`: CI para Python, que ejecuta las pruebas con pytest.
- `calculadora.py` y `test_calculadora.py`: el código y su prueba.

Cada push lanza los dos workflows. Para verlo, cambia el comentario de `calculadora.py`, haz commit y abre la pestaña **Actions**.

Para ver una prueba que falla, cambia `a + b` por `a - b` y haz commit: el workflow de Python sale en rojo.
