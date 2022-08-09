### Hi! 👋

If you reached this page you either have an ArC Instruments characterisation
tool, want to develop software for one or both! If you are new to ArC Instruments
tools read, otherwise the main repositories are further down this page 👇


### I have an ArC ONE

If you have an ArC ONE your first stop would be to download and install our
[ArC ONE Control Panel](https://github.com/arc-instruments/arc1_pyqt)
application (ArC1PyQT). You can use it right out of the box to characterise
two-terminal devices.

A comprehensive
[manual](http://files.arc-instruments.co.uk/documents/ArC_One.pdf) is available
to better familiarise yourself with your ArC ONE.

If the built-in functionality is not enough you can develop your own
experiments.  ArC1PyQT comes with
[SuperMode](http://files.arc-instruments.co.uk/documents/manual/index.html#supermode)
which allows you to combine different experiments in one seamless workflow.
Alternatively you can get on with developing your own experiment panels.
ArC1PyQT built-in modules are built with the same infrastructure so dive-in the
code to get started.

For automated or headless applications we provide
[libarc1](https://github.com/arc-instrument/libarc1) which is a Python library
that exposes most of the tool's functionality.


### I have an ArC TWO

If you have our latest and greatest tool you can download
[ArC2Control](https://github.com/arc-instruments/arc2control) built with
similar goals in mind as ArC1PyQT. It will allow you to start experimenting
with two-terminal DUTs. Refer to our
[documentation](http://files.arc-instruments.co.uk/documents/arc2control/latest/index.html)
for a quick start guide.

ArC2Control is itself extensible with custom experiment panels. If that
interests you check our [developer's
documentation](http://files.arc-instruments.co.uk/documents/arc2control/latest/api_modules.html).

Although ArC2Control is built for two-terminal crossbar DUTs in mind ArC TWO
itself is a much more flexible tool. If you want to tailor the capabilities of
ArC TWO for your own bespoke experiments you can do so with
[pyarc2](https://github.com/arc-instruments/pyarc2), the Python library which
exposes all the low-level functionality of ArC TWO. ArC2Control itself is built
on pyarc2. To get started check our
[docs](http://files.arc-instruments.co.uk/documents/pyarc2/latest/index.html).


### I have a question

All of our public repositories have a discussion board so if you have a question
for any specific component feel free to open a topic.
