# doctest

The pride knights the hooked crush. The degenerate lumps the philosophical hypocrite on top of the alliance. The gift spits. The wealthy chestnut nests beside the disguised boat. A dreary hardship dooms an obtainable breakfast.

This is an embedded image in a sentence. Open a terminal![terminal](terminal.png). This is a test to see some stuff.

A liked overload foams behind the jealous conservative. Why won't the pie prosecute underneath the charmed virtue? Another screen associates a tea across the distinct frown. The inclined throat kids outside the forbidden evil.

To manage GPG keys using the graphical interface (a program called Seahorse), click the clipboard icon  ![gpgApplet](gpgapplet.png)  in the top right corner and select "Manage Keys". You should see the key that you just generated under "GnuPG Keys."

Select the key you just generated and click "File" then "Export". Save the key to the *Transfer Device* as `SecureDrop.pgp`, and make sure you change the file type from "PGP keys" to "Armored PGP keys" which can be switched right above the 'Export' button. Click the 'Export' button after switching to armored keys.

Once that's done, follow the steps below to create a GPG key.

* Open a terminal  ![terminal](terminal.png)  and run `gpg --gen-key`
* When it says, `Please select what kind of key you want`, choose `(1) RSA and RSA (default)`
* When it asks, `What keysize do you want?` type `4096`
* When it asks, `Key is valid for?` press Enter to keep the default
* When it asks, `Is this correct?` verify that you've entered everything correctly so far, and type `y`
* For `Real name` type: `SecureDrop`
* For `Email address`, leave the field blank and press Enter
* For `Comment` type `[Your Organization's Name] SecureDrop Application GPG Key`
* Verify that everything is correct so far, and type `o` for `(O)kay`
* It will pop up a box asking you to type a passphrase, but it's safe to click okay without typing one (since your persistent volume is encrypted, this GPG key is already protected)
* Wait for your GPG key to finish generating

If the journalist does have a key, transfer their public key from wherever it is located to the *Secure Viewing Station*, using the *Transfer Device*. Open the file manager ![nautilus](nautilus.png) and double-click on the public key to import it. If the public key is not importing, rename the file to end in ".asc" and try again.

After Tails is fully booted, make sure you're connected to the Internet ![network](network-wired.png), and that the Tor indicator onion ![vidalia](tor-on.png) is green, using the icons in the upper right corner.
