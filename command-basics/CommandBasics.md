# Command Basics

In Linux, you can enter commands when your command prompt (`$`) is visible. Commands are case-sensitive, so be mindful of capitalization, especially in command options.

## Basic Command Structure

A typical command follows this structure:

``` command -option arguments ```

Options often come before arguments. In some commands, this order is required; in others, it's optional.

## Options and Arguments

### Single vs. Separate Options

Options can be combined or separated. For example:

``` ncal -3h ```

is equivalent to:

``` ncal -3 -h ```

### Short vs. Long Form Options

Some commands support both short and long form options, though not all commands do.

**Short Form**: Starts with a single dash (`-`), like `-u` in `date -u`.

**Long Form**: Starts with double dashes (`--`), like `--universal` in `date --universal`.

**Note: Long form options cannot be combined and must each be separated by a space.**

### Combining Options and Arguments

If an option requires an argument, it can sometimes be combined without a space:

```
ncal -B 1 -A 1

ncal -B1 -A1
```

### Mixing Options With and Without Arguments

When using options with arguments alongside options without arguments, separate them for clarity:

``` ncal -3h -B1 -A1 ```

## Examples

### List Files in a Directory

``` ls -l ```

Shows a detailed list of files in the current directory.

### Display Calendar with Context

``` ncal -B1 -A1 ```

Displays a calendar with one month before and after the current month.

## Quick Tips

Common Flags: Many commands use similar flags for convenience:
* `-h` or `--help`: Display help information
* `-a` or `--all`: Show all items, including hidden ones
* `-l`: List items in long format (e.g., `ls -l`)

Error Handling: If you get a "command not found" error, double-check spelling and capitalization, or verify the command is installed.
