Test using https://github.com/RightTyper/RightTyper

Here are the commands that I ran

python -m righttyper -m torch --type-coverage-by-directory torch

Produces: righttyper-coverage.html

cd test

Generate files with types
python3 -m righttyper -m pytest --continue-on-collection-errors quantization/bc/ --infer-shapes --output-files


Overwrite in place
python3 -m righttyper -m pytest --continue-on-collection-errors quantization/bc/ --infer-shapes --output-files --overwrite


