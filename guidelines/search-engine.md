# Search Engine

To change your search engine, click on the **Menu** button, go to **Settings**, then **Search Engine.** And choose your search engine:

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

### Custom Engine:

We don't currently support custom search engines. If you want to have a custom search engine you'll have to do it manually. If you think that's an important feature, open an issue on [GitHub](https://github.com/PocketStudios/Pocket-Browser/issues).

* Open your file manager.
* Go to the browser configuration folder:

**Windows:** C:\Users\\{User}\AppData\Local\pocket-browser\\

**Linux:** \~/.config/pocket-browser

**Mac:** \~/Library/Application Support/pocket-browser

* Open the `search.pocket`file.
* Put the search engine link and put `%s` where search query should be provided.

**Example:** `https://google.com/%s`

* Restart the browser.



