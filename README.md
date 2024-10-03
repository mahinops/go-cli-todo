# Go Todo CLI

### Step 1: Download the Binary

Users can download the binary using either `curl` or `wget`. Here’s how they can do it:

 **Using `curl`**:
   Open a terminal and run the following command:
   ```bash
   curl -L -o todo https://github.com/mahinops/go-cli-todo/releases/download/v1.0.0/todo
   ```


### Step 2: Make the Binary Executable

After downloading the binary, users need to make it executable. They can do this with the following command:
```bash
chmod +x todo
```

### Step 3: Move the Binary to a Directory in PATH

To run the `todo` command from anywhere, users should move the binary to a directory that is in their system's `PATH`, such as `/usr/local/bin`. They can do this using the following command:
```bash
sudo mv todo /usr/local/bin/
```

### Step 4: Verify the Installation

Users can verify that the installation was successful by running:
```bash
todo -help
```

This should display the help information for your CLI tool, confirming that it’s installed and ready to use.

### Summary of Commands

Here’s a summary of the commands users need to run to download and install your CLI tool:

```bash
# Step 1: Download the binary
curl -L -o todo https://github.com/mahinops/go-cli-todo/releases/download/v1.0.0/todo

# Step 2: Make the binary executable
chmod +x todo

# Step 3: Move it to a directory in PATH
sudo mv todo /usr/local/bin/

# Step 4: Verify the installation
todo -help
```
