
01-answer: pyenv-stamp
	false

pyenv-stamp: pyrequirements.txt
	test -d pyenv || python3 -m venv pyenv
	pip install -r $<
	touch $@

clean:
	rm -vf ??-answer
	rm -vrf pyenv pyenv-stamp
