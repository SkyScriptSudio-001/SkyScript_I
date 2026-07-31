# SkyScript

> A lightweight, high-performance interpreted scripting language designed for automation, rapid task execution, and web embedding.
>  💡 **Tip**: Click on the **Editor** button or navigate to `intl/editor.html` in your browser to launch the online code editor instantly.

---

## 🌟 Features

* **Lightweight & Fast**: Built for efficient text and script parsing with minimal overhead.
* **Modern IDE Support**: Fully compatible with web-based environments featuring custom syntax highlighting and code formatting.
* **Smart Flow Control**: Includes flexible script blocks and block-skipping mechanisms (`skip to ... here`).
* **Cross-Platform**: Easily embeddable and deployable across various systems.

---

## 📖 Quick Start

Here is a simple example of a SkyScript (`.sky`) program:

```skyscript
set prog
    set window.title "SkyScript International Edition"
    set window.size "1200x800"
    
    ## This is a test comment
    print "Welcome to SkyScript Global IDE!"
    
    def class UserDemo
        name = "Sky"
        score = "100"
        print name
    
    skip to
        This code block will be skipped automatically.
    here
    
    print "Execution finished successfully!"
end prog
