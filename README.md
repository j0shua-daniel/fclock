# fclock
A simple, fast, fuzzy clock!

![fclock](https://github.com/j0shua-daniel/images/blob/main/fclock.png?raw=true)

![fclock-lolcat](https://github.com/j0shua-daniel/images/blob/main/fclock-lol.png?raw=true)

Please watch the [video](https://asciinema.org/a/EK7473jODgOD6Sh7yJGDA8XUu)!

If there are any issues open and [issue](https://github.com/j0shua-daniel/fclock/issues)

## Install

You will need `figlet` (found in most OS repos) installed.

If you want the clock to be multicolored then you will need `lolcat` to be installed.

```
sudo curl -o /usr/bin/fclock https://raw.githubusercontent.com/j0shua-daniel/fclock/refs/heads/main/fclock
sudo chmod +x /usr/bin/fclock
```

## Usage

Just run `fclock` to get the default clock.

Run `fclock | lolcat` to get the multicolored clock.

Do `ctrl+c` to stop the clock.

## Todo

- [ ] Remove figlet dependency.
- [ ] Make it faster.
- [ ] Enable a way to quit it without needing to do `ctrl+c`.

