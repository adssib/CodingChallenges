## Steps to Recreate the 'wc' Command

1. **Create the script:**
```bash
nano mywc
```
2. **Make the script executable:**
```bash
chmod +x mywc
```
3. **Create a bin directory in home folder:**
```bash
mkdir -p ~/bin
```
4. **Copy the script to the bin directory:**
```bash
cp ~/mywc ~/bin
```
5. **Add bin directory to PATH:**
```bash
echo 'export PATH="$HOME/bin:$PATH"' >> ~/.bashrc
```
6. **Reload bash configuration:s**
```bash
source ~/.bashrc
```
7. **Finally test the command by passwing to it a path**
```bash
mywc path/to/test/file
```

