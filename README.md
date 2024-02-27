# Aim of the project
This is intended to be an open repository where my master thesis' notes will be saved, making them available for anyone to contribute on the subject: The Calderon Problem.

# Installation of LaTeX libraries

- To install the LaTeX libraries in Ubuntu please do:
> wget https://mirror.ctan.org/systems/texlive/tlnet/install-tl-unx.tar.gz

- Unzip the .tar.gz file by right-clicking, for example.

- Go inside the folder:
> cd Downloads/install-tl-unx/

- If needed to refresh LaTeX library:
> sudo texhash

- To check LaTeX version:
> latexmk --version

- If ever needed to use a library that is not already installed by the previous installation, paste the .sty file of the desired library within the same folder of the .tex file or reference it as:
> \usepackage{package_folder/package_file}
