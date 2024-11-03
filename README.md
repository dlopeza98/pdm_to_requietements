# pdm_to_requietements

Install pdm:

1. pdm init
2. pdm python install 3.12.2
3. pdm install

Import libraries in pdm

- `pdm add`

export pdm to requierements

- pdm plugin add export
- pdm export -o requirements.txt --without-hashes --prod
