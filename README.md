# Dotfiles for Pho3nixHun

Welcome to my dotfiles repository! This is where I store all my configuration files, setup scripts, and other resources to streamline my development environment across different systems. Because setting up from scratch every time is so last decade.

## Why?

As a fan of [WET](https://en.wikipedia.org/wiki/Don't_repeat_yourself#WET) things in life, but keeping my code [DRY](https://en.wikipedia.org/wiki/Don't_repeat_yourself), this repository helps me avoid the repetitive madness of configuring my environment from scratch every single time. 
Feel free to use and adapt these files to suit your needs, though let's be honest—I'm probably the only one who's going to use this.

## What's Inside?

Here's a checklist of what you can find here, along with what's planned for future additions:

- [ ] **Setup Script for Debian**: Installs all required software and customizes the shell.
- [ ] **Oh My Zsh Config Files**: My personalized Zsh configurations.
- [ ] **PowerLevel10K Config**: P10K setup for a visually pleasing terminal.
- [ ] **SSH Config**: Custom `.ssh/config` for SSH connections.
- [ ] **.devcontainer Setup**: Configuration for development containers.
- [ ] **Terminal Fonts**: Fonts used in the terminal and VSCode.
- [ ] **VSCode Settings**: My VSCode settings file.
- [ ] **Windows Setup Readme**: Instructions and setups for my Windows environment.
- [ ] **Shell Aliases**: Handy aliases for the Linux shell.
- [ ] **Unattended Windows Installer**: A potential addition for Windows installation automation.
- [ ] **Wallpapers**: A collection of wallpapers I use.

## Usage

Since I'm likely the primary (if not only) user of these dotfiles, here's a quick guide—for my future self:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/Pho3nixHun/dotfiles.git
    cd dotfiles
    ```

2. **Run the setup script** (for Debian systems):
> While all the cool kids are off ricing their Arch setups, I'm over here sticking with Debian like a creature of habit. Because sometimes stability is more important than street cred... or I'm just lazy.

    ```sh
    ./setup_debian.wsl.sh
    ```

3. **Customize your environment**:
    - Copy `.zshrc` and `.p10k.zsh` to your home directory.
    - Apply the SSH configuration, and VSCode settings as needed.
    - Install the fonts provided.

4. **Explore and modify**: Make the configs your own. Feel free to edit, add, or remove as per your preferences.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

If anyone besides me stumbles upon this and has suggestions or improvements, feel free to open an issue or submit a pull request. Let's make our setups efficient together!

---

Sure, let's break it down and format it for better readability:

## Note

Some files and configurations are tailored to my personal preferences and may not be universally applicable. Use with caution and adapt as necessary.

As a self-proclaimed jolly joker in the programming world, I dabble in a bit of everything:

- Architect: Pretty good, according to my co-workers.
- Tech Lead: Excellent, or so they say.
- UX Researcher & UI Designer: Not half-bad if you hand me a few users and a Figma license. I'll get them to spill all their secrets (about the product, of course).

But primarily, I'm a Frontend guy; I thrive in the chaos. Backend? Too chill for my taste. I prefer my mornings filled with stress, courtesy of the PO dumping today's urgent changes right on my head. Ah, the sweet symphony of impending deadlines!
So these dotfiles and scripts are mainly orbiting around my most-used tools:

- Docker
- Git
- NodeJS
- TypeScript
- With a sprinkle of Angular magic

It's all about keeping things fast, tidy, dynamic and occasionally breaking for no apparent reason—just the way I like it 😏
