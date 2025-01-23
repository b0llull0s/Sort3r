# Sort3r
- Sorter is a simple Bash script designed to extract, normalize, and deduplicate URLs from files.
- It’s especially useful when working with output from multiple tools or files containing URLs.
- The script ensures all URLs are standardized with a trailing `/`, making it ideal for compatibility with tools like `GoWitness`.
## Usage
- Copy the script to your `/usr/bin` folder:
```
sudo cp sorter /usr/bin/
```
- Make it executable:
```
chmod +x /usr/bin/sorter
```
- And run it:
```
sorter -i input_file.txt -o output_file.txt
```
## Contributing
- Feel free to open issues or submit pull requests to improve the script.
