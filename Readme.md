# King Tutte Datamap Codex

This repo, [the King Tutte Datamap Codex](https://github.com/Connoiter/king_tutte_datamap_codex)
is a Jupyter Book (v2) full of datamapping notebooks design
to run on [Google's Colab](https://colab.research.google.com/) Jupyter
service.

<div align="center">
    <img src="./images/tut/king_tutte_on_colab.transparent_bg.png" width="100%" />
</div>

This repo can stand alone by itself but it is also used as a part of
[the King Tutte
Scrolls](https://github.com/Connoiter/king_tutte_scrolls). Together
the two are the King Tutte Datmap SDK. The Scrolls is an **Agent
Skill**, as [defined by Anthropic](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills).
This Codex is included as a submodule in the Scrolls. 

The core software (UMAP, HDBSCAN, Toponomy, EVōC, DataMapPlot, etc.)
is technology out of the Tutte Institute, including most of the
notebooks. Note that this project and its lighthearted tone are the
product of [Connoiter](https://connoiter.com); The Tutte Institute had
nothing to do with the Codex (except having done all the hard work).

The main value of this project is to gather various pre-existing
datamap generating sample code into one currated resource (the Codex --
this repo -- which can be built into a Jupyter Book) and ensure that
they all run as notebooks on Colab.

1. If a pre-existing resource is a Jupyter notebook (*.ipynb file), it
   is modified as needed to get it to work out of the box on Colab.
2. If a pre-existing resource is a Python script (*.py file) the code
   is repackaged as a Jupyter notebook and tweaked for execution on
   Colab.

This Codex was developed for use during conference workshops but also
serves well for self-study of how to make King Tutte pipelines, which
produce datamaps. For use of the Codex within an Agent Skill, see
[the King Tutte Datamap Scrolls(https://github.com/Connoiter/king_tutte_scrolls)
which includes this Codex as a git submodule.

## Etymology

The Scrolls project started before the Codex repo. Actually the latter
was forked out of the former.

The name, Scrolls, being plural implies multiple separate scrolls
because that project is essentially just an agglomeration of multiple
separate repos (each a scroll in this metaphor) into one unit which
can be packaged as an Agent Skill.

The Codex is a Jupyter Book ergo the name, Codex. (A codex is an
ancient type of book wherein individual sheets of paper are bound on
one side, as distinct from modern books which might have signatures,
that is, pages folded in half and then bound to seem like two pages,
etc.). Both scrolls and codices could be made of papyrus.

"A book in a collection of scrolls? Wha?" If really necessary then the
metaphor could be tortured by saying a codex can be unbound and then
the pages rebound as a scroll. Actually, in the case of the Scrolls
the Jupyter notebooks (*.ipynb files) are repurposed into markdown
files (the default file type of Agent Skills. So take that, you pedants :P

