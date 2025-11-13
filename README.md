# Dice Rolling

A tiny interactive Python script that simulates rolling two six-sided dice.

The program repeatedly prompts the user with `Roll the dice? (y/n):`:
- Enter `y` to roll two dice (each 1–6). The script prints the tuple result and a running roll count.
- Enter `n` to quit; the program prints a goodbye message with the total roll count.
- Any other input prints `Invalid choice!` and re-prompts.

**Quick start**

Requirements:
- Python 3.x

How to Run the Game:
```bash
python3 dice-rolling.py
```

**Example session**

```
Roll the dice? (y/n): y
(3, 5)
You have rolled the dice 1 time(s).
Roll the dice? (y/n): y
(6, 2)
You have rolled the dice 2 time(s).
Roll the dice? (y/n): maybe
Invalid choice!
Roll the dice? (y/n): n
Thanks for playing! You rolled the dice 2 time(s).
```

**Notes & next steps**

- The current script always rolls exactly two six-sided dice and is interactive only.
- Possible improvements: add CLI options to choose number/sides of dice, add a non-interactive mode for scripting, or export statistics to a file.

## Contributing

Contributions are welcome. Open a pull request against the `main` branch and describe your changes.

## License

See the [LICENSE](LICENSE) file for details.

