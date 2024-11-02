# AInnotate

Annotate Python scripts with `docstring`s using AI.

## Usage

TL, DR: Clone the code and see the help message.

Long version:

First, clone this code:

```shell
git clone https://github.com/Dandelight/ainnotate.git
```

Then, set environment variables `OPENAI_API_KEY` and (optionally) `OPENAI_BASE_URL`.

This file depends on `openai` and `astor`. You can install them with

```shell
pip install openai astor
```

It is recommended to install the dependencies in a virtual environment.

Finally, run

```shell
python ainnotate.py [path]
```

where `[path]` should be replaced with the path to the Python code you want to annotate.

> Reminder: in the command line, if your path contains `space`s, don't forget to surround it with quotation marks.
