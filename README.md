# Little Open Ticket System [![](https://travis-ci.org/diffsky/LOTS.png)](https://travis-ci.org/diffsky/LOTS)

**LOTS** is a simple ticketing system for code. Using twitter style tagging, you can add a `#comment` with a `!tag` and a `^priority`. These are then presented in a web interface. **LOTS** can optionally just find any mention of the word _"TODO"_ in your code.

Here is an example of a snippet that would be picked up by **LOTS**:

    # This readme should be improved !documentation ^2

### Installation

Install lots globally via npm:

    $ [sudo] npm i -g lots


### Usage

In a directory you wish to review your code from, run:

    $ LOTS

Then visit `http://localhost:5000/` to see the report.

See `LOTS -h` for more options


---

LOTS was inspired by [BANG](http://www.thecodebase.com/bang/), which now seems defunkt.
