### What if the global internet goes down and you need AI's help?
Here is the text transformed into a direct, engaging guide intro in English:

Imagine the entire global internet crashes tomorrow—ChatGPT, Google, and all your favorite web tools vanish overnight, leaving your browser stuck on the offline dinosaur screen. If you rely on AI for your daily study or work routine, that sudden outage could throw everything into chaos.

Whether you are traveling off the grid or facing a sudden network blackout, there is a simple tool that can save you: an ordinary USB flash drive that might be sitting forgotten on your desk right now.

This guide demonstrates how to load a complete, functional AI model directly onto a USB drive. Once set up, you can carry your own personal AI assistant anywhere and run it completely offline on any computer, without needing an internet connection.

To use it, simply plug the USB drive into your device. Your computer will handle everything else completely offline—delivering a smooth and professional experience. Given its response quality and speed, you won't even feel like you're running a local AI offline directly from a portable flash drive.

### Step-by-Step Guide

**1. Preparing the USB Drive**

* Connect your USB drive (pen drive) to your laptop or PC.
* Open **This PC / File Explorer**, right-click on the USB drive, select **Format**, and format it.

**2. Downloading llamafile**

* Open your browser and search for `llamafile github` on Google.
* Open the first GitHub link (`mozilla-ai/llamafile`).
* On the right panel under **Releases**, click on the latest release version (e.g., `llamafile v0.10.6`).
* Scroll down to the **Assets** section and click to download `llamafile-0.10.6` (or the version available).
* Once downloaded, go to your **Downloads** folder, rename the file, and append `.exe` to the end (e.g., `llamafile-0.10.6.exe`).

**3. Downloading the AI Model**

* Go to Google and search for `Hugging Face`.


* Open the Hugging Face website and click on **Models** at the top.


* Under Libraries, select **GGUF**.


* Search for `qween` (Qwen) in the search bar and select `Qwen3_4B_thinking_finetune` (or your preferred Qwen GGUF model).


* Go to the **Files and versions** tab and click the download icon next to the `.gguf` file (e.g., `qwen3-4b-thinking-2507.Q4_K_M.gguf`).



**4. Transferring Files to USB Drive**

* Cut/move both downloaded files (`llamafile-0.10.6.exe` and the `.gguf` model file) directly into your formatted USB drive.



**5. Creating the Execution Script**

* Open **Notepad** and paste/type the following command:



```text
.\llamafile-0.10.6.exe --server --model qwen3-4b-thinking-2507.Q4_K_M.gguf

```

(Note: Replace the file names in the command with the exact file names present in your USB drive).

* Click **File > Save As...**.


* Set the save location to your USB drive.


* Name the file `start.bat` and click **Save**.



---

### Running the AI Offline

* Plug the USB drive into any PC or laptop.


* Open the USB drive and double-click `start.bat`.


* A terminal window will launch and display local server links, such as `[http://127.0.0.1:8080](http://127.0.0.1:8080)`.


* Copy the URL, open any browser (completely offline), paste the URL into the address bar, and press **Enter**.


* The web interface will load, allowing you to chat with your local offline AI model.
