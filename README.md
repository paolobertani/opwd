# opwd - open parent working direcory

-

&nbsp;

On **macOS** opens the parent working directory on a new window in the **Finder**

&nbsp;

### Installation:

Make the script executable:

```bash
chmod 755 opwd
```

If necessary create a `bin/` directory into `/usr/local`...

```bash
sudo mkdir /usr/local/bin
```

...and add it to `PATH` environment variable in `~/.zshenv`

```
export PATH=/usr/local/bin:$PATH
```

Finally:

```bash
sudo cp opwd /usr/local/bin/opwd
```

&nbsp;

### Usage:

From the terminal:

```bash
 % opwd
```















