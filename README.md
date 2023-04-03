# Fractal Mapper

A modular fractal mapping tool for FATD..D or only fractal mapping standalone.

What is fractal mapping?



Fractal mapping is a subpattern of the FATD..D development pattern. Fractal mapping is a way to track over time coverage within and between categories of source code. The tracking can branch, crossreference or be recursive. For this reason I'm calling it fractal. Does not have to perfectly fit the mathmatical definition of fractals. Fractal mapping can also track, add, modify, or remove metadata. The recursion can carry over from different categories providing

<a title="Rafael Ruggiero, CC BY-SA 4.0 &lt;https://creativecommons.org/licenses/by-sa/4.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Fractal_tree.gif"><img width="256" alt="Fractal tree" src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Fractal_tree.gif"></a>

## Example categories of mapping (in mostly FATD..D view):
- Tests to Working Implmentation Code (Green)
  - Why: Knowing your code coverage is always useful. Feel free to rerun all your tests or use commit diffs. But this is another way to track it.
- Tests to Failing Code (Red)
  - Why: If you have to refactor your tests this makes it easier to replay and adapt if the reference is kept somewhere. This also serves as proof of human effort. And serves to help with reference source.
- Acceptance(s) to Test(s)
  - Why: This helps track what requirments are being implemented where, and if requirements change what source might be affected. Consider this as another way keeping your code organized. File folders are great but this also helps track relationships between sections of those files.
- External references to Acceptance:
  - Why: This can help track things like API changes, changes in standards, changes in laws. Those can then chain reflect down on to tests and source code as well.
- Acceptance criteria to external documents
  - Why: If your documentation is in antoher repo or inside a database. This can help identify breaking changes in documentation.

## Installing
`todo`

## Use

### Configuration / Options
Specifying the behaivor maybe be done via combinations of several methods:
- Configuration files
- Environment variables
- Terminal command arguments
- API calls

### Running
The factal mapper may be run through three methods:
- Commandline
- JavaScript API
- GitHub Action

## Credits
Fractal Tree Gif by  <a href="https://commons.wikimedia.org/wiki/File:Fractal_tree.gif">Rafael Ruggiero</a>, <a href="https://creativecommons.org/licenses/by-sa/4.0">CC BY-SA 4.0</a>, via Wikimedia Commons
