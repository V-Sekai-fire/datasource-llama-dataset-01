# datasource-llama-dataset-01

Grammar-constrained generation with a local language model: GBNF grammars that make it emit Godot scene text or JSON arrays.

## What it is for

A grammar narrows the sampler to output that parses, so a generated scene is valid scene text by construction. The scene grammars describe the text scene format; the JSON grammar constrains a prompt's answer to an array.

## Run

```sh
pip install -r requirements.txt
cd TEST_01_tscn
python llama-cpp-grammar.py
```

The scripts open their grammar from the current directory, and download their model on first run.

## Licence

The scripts carry MIT SPDX headers; the repository has no licence file.
