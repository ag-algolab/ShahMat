# ♟️ ShahMat

[![PyPI version](https://img.shields.io/pypi/v/shahmat.svg)](https://pypi.org/project/shahmat/)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**ShahMat** is a Python package that leverages the official [Chess.com API](https://www.chess.com/news/view/published-data-api) to **fetch, analyze, and visualize your games**.  
It is part of the **AG Algo Lab** initiative: making finance & tech accessible to everyone — and yes, sometimes we have fun applying data science to chess too!

The name *ShahMat* comes from the ancient expression that later gave birth to the word **“checkmate”** :)  

---

## Quick Start 🚀

Install & Use ShahMat:
```bash
!pip install ShahMat

from ShahMat import chesscom
chesscom('your_username', start_year=2024)
