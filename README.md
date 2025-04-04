# Lesson-1
Welcome to your first lesson!

##  Generating an SSH key and adding it to your profile

Run `ssh-keygen -t ed25519` in your terminal and hit enter until it stops prompting. Note the path where it is creating the key.
Navigate to the path where the key has been created. This will typically be in `~/.ssh`.
Print the public key to the terminal so it can be copied by running cat `~/.ssh/id_ed25519.pub`