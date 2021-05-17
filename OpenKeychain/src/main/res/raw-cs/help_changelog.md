[//]: # (Poznámka: Prosím, vložte každou větu na zvláštní řádek, Transifex vkládá každý řádek do vlastního překladového pole!)

## 5.6
  * Compatibility with Android 10 and higher
  * Several bug fixes

## 5.5
  * Oprav dešifrování ze schránky v Androidu 10

## 5.4
  * Přidej metodu WKD Advanced 
  * Přidej obchod COTECH Security Key

## 5.3
  *  Použij keys.openpgp.org jako výchozí keyserver

## 5.2
  * Vylepšen import klíčů ze schránky

## 5.1
  * Podpora pro Ledger Nano S
  * Podpora hledání v Web Key Directory (WKD)
  * Opraven potenciální problém s bezpečností API

## 5.0
  * Vylepšena podpora Autocrypt

## 4.9

  * Podpora Curve25519
  * Vylepšena podpora pro bezpečnostní tokeny

## 4.8

  * Vylepšena podpora pro USB tokeny: Gnuk Nitrokey modely, YubiKey 4 modely
  * Funkce k nalezení pozice NFC snímače zařízení

## 4.7

  * Improved import from clipboard
  * New key creation wizard for Security Tokens
  * Removed password cache "time to live" setting


## 4.6

  * Import your keys using our new Secure Wi-Fi Transfer mechanism


## 4.5

  * Detailed description of security problems
  * Display keyserver status per key
  * Support for EdDSA
  * Fix pgp.mit.edu (new certificate)


## 4.4

  * New key status displays detailed information why a key is considered insecure or defective


## 4.3

  * Better support for large keys
  * Fix import of Gpg4win files with broken encodings


## 4.2

  * Experimental support for Elliptic Curve Encryption with Security Tokens
  * Redesigned key import screen
  * Design improvements to key lists
  * Support for keyserver onion addresses


## 4.1

  * Better detection of emails and other content when opened


## 4.0

  * Experimental support for Security Tokens over USB
  * Allow password changing of stripped keys


## 3.9

  * Detection and handling of text data
  * Performance improvements
  * UI improvements for Security Token handling


## 3.8

  * Redesigned key editing
  * Choose remember time individually when entering passwords
  * Facebook key import


## 3.7

  * Improved Android 6 support (permissions, integration into text selection)
  * API: Version 10


## 3.6

  * Encrypted backups
  * Security fixes based on external security audit
  * YubiKey NEO key creation wizard
  * Basic internal MIME support
  * Automatic key synchronization
  * Experimental feature: link keys to Github, Twitter accounts
  * Experimental feature: key confirmation via phrases
  * Experimental feature: dark theme
  * API: Version 9


## 3.5

  * Key revocation on key deletion
  * Improved checks for insecure cryptography
  * Fix: Don't close OpenKeychain after first time wizard succeeds
  * API: Version 8


## 3.4

  * Anonymous key download over Tor
  * Proxy support
  * Better YubiKey error handling


## 3.3

  * New decryption screen
  * Decryption of multiple files at once
  * Better handling of YubiKey errors


## 3.2

  * First version with full YubiKey support available from the user interface: Edit keys, bind YubiKey to keys,...
  * Materiální téma
  * Integration of QR Code Scanning (New permissions required)
  * Vylepšen průvodce založení klíče
  * Oprava chybějícího kontaktu po synchronizaci
  * Vyžaduje se Android 4
  * Přepracován panel klíčů
  * Zjednodušit krypto volby, lepší výběr bezpečných šifer 
  * API: Oddělené podpisy, volný výběr podpisového klíče,...
  * Oprava: Některé platné klíče byly zobrazeny jako zrušené nebo za lhůtou platnosti
  * Nepřijímat podpisy zrušenými klíči nebo klíči za lhůtou platnosti
  * Podpora Keybase.io v panelu pokročilé
  * Method to update all keys at once


## 3.1.2

  * Opraven export klíčů do souboru (nyní skutečně)


## 3.1.1

  * Fix key export to files (they were written partially)
  * Fix crash on Android 2.3


## 3.1

  * Fix crash on Android 5
  * New certify screen
  * Secure Exchange directly from key list (SafeSlinger library)
  * New QR Code program flow
  * Redesigned decrypt screen
  * New icon usage and colors
  * Fix import of secret keys from Symantec Encryption Desktop
  * Experimental YubiKey support: Subkey IDs are now checked correctly


## 3.0.1

  * Better handling of large key imports
  * Improved subkey selection


## 3.0

  * Propose installable compatible apps in apps list
  * New design for decryption screens
  * Many fixes for key import, also fixes stripped keys
  * Honor and display key authenticate flags
  * User interface to generate custom keys
  * Fixing user ID revocation certificates
  * New cloud search (searches over traditional keyservers and keybase.io)
  * Support for stripping keys inside OpenKeychain
  * Experimental YubiKey support: Support for signature generation and decryption


## 2.9.2

  * Fix keys broken in 2.9.1
  * Experimental YubiKey support: Decryption now working via API


## 2.9.1

  * Split encrypt screen into two
  * Fix key flags handling (now supporting Mailvelope 0.7 keys)
  * Improved passphrase handling
  * Key sharing via SafeSlinger
  * Experimental YubiKey support: Preference to allow other PINs, currently only signing via the OpenPGP API works, not inside of OpenKeychain
  * Fix usage of stripped keys
  * SHA256 as default for compatibility
  * Intent API has changed, see https://github.com/open-keychain/open-keychain/wiki/Intent-API
  * OpenPGP API now handles revoked/expired keys and returns all user ids


## 2.9

  * Fixing crashes introduced in v2.8
  * Experimental ECC support
  * Experimental YubiKey support: Only signing with imported keys


## 2.8

  * So many bugs have been fixed in this release that we focus on the main new features
  * Key edit: awesome new design, key revocation
  * Key import: awesome new design, secure keyserver connections via hkps, keyserver resolving via DNS SRV records
  * New first time screen
  * New key creation screen: autocompletion of name and email based on your personal Android accounts
  * File encryption: awesome new design, support for encrypting multiple files
  * New icons to show status of key (by Brennan Novak)
  * Important bug fix: Importing of large key collections from a file is now possible
  * Notification showing cached passphrases
  * Keys are connected to Android's contacts

This release wouldn't be possible without the work of Vincent Breitmoser (GSoC 2014), mar-v-in (GSoC 2014), Daniel Albert, Art O Cathain, Daniel Haß, Tim Bray, Thialfihar

## 2.7

  * Purple! (Dominik, Vincent)
  * New key view design (Dominik, Vincent)
  * New flat Android buttons (Dominik, Vincent)
  * API fixes (Dominik)
  * Keybase.io import (Tim Bray)


## 2.6.1

  * Some fixes for regression bugs


## 2.6

  * Key certifications (thanks to Vincent Breitmoser)
  * Support for GnuPG partial secret keys (thanks to Vincent Breitmoser)
  * New design for signature verification
  * Custom key length (thanks to Greg Witczak)
  * Fix share-functionality from other apps


## 2.5

  * Fix decryption of symmetric OpenPGP messages/files
  * Refactored key edit screen (thanks to Ash Hughes)
  * New modern design for encrypt/decrypt screens
  * OpenPGP API version 3 (multiple api accounts, internal fixes, key lookup)


## 2.4
Thanks to all applicants of Google Summer of Code 2014 who made this release feature rich and bug free!
Besides several small patches, a notable number of patches are made by the following people (in alphabetical order):
Daniel Hammann, Daniel Haß, Greg Witczak, Miroojin Bakshi, Nikhil Peter Raj, Paul Sarbinowski, Sreeram Boyapati, Vincent Breitmoser.

  * New unified key list
  * Colorized key fingerprint
  * Support for keyserver ports
  * Deactivate possibility to generate weak keys
  * Much more internal work on the API
  * Certify user ids
  * Keyserver query based on machine-readable output
  * Lock navigation drawer on tablets
  * Suggestions for emails on creation of keys
  * Search in public key lists
  * And much more improvements and fixes…


## 2.3.1

  * Hotfix for crash when upgrading from old versions


## 2.3

  * Remove unnecessary export of public keys when exporting secret key (thanks to Ash Hughes)
  * Fix setting expiry dates on keys (thanks to Ash Hughes)
  * More internal fixes when editing keys (thanks to Ash Hughes)
  * Querying keyservers directly from the import screen
  * Fix layout and dialog style on Android 2.2-3.0
  * Fix crash on keys with empty user ids
  * Fix crash and empty lists when coming back from signing screen
  * Bouncy Castle (cryptography library) updated from 1.47 to 1.50 and build from source
  * Fix upload of key from signing screen


## 2.2

  * New design with navigation drawer
  * New public key list design
  * New public key view
  * Bug fixes for importing of keys
  * Key cross-certification (thanks to Ash Hughes)
  * Handle UTF-8 passwords properly (thanks to Ash Hughes)
  * First version with new languages (thanks to the contributors on Transifex)
  * Sharing of keys via QR Codes fixed and improved
  * Package signature verification for API


## 2.1.1

  * API Updates, preparation for K-9 Mail integration


## 2.1

  * Lots of bug fixes
  * New API for developers
  * PRNG bug fix by Google


## 2.0

  * Complete redesign
  * Share public keys via QR codes, NFC beam
  * Sign keys
  * Upload keys to server
  * Fixes import issues
  * New AIDL API


## 1.0.8

  * Basic keyserver support
  * App2sd
  * More choices for passphrase cache: 1, 2, 4, 8, hours
  * Translations: Norwegian Bokmål (thanks, Sander Danielsen), Chinese (thanks, Zhang Fredrick)
  * Bugfixes
  * Optimizations


## 1.0.7

  * Fixed problem with signature verification of texts with trailing newline
  * More options for passphrase cache time to live (20, 40, 60 mins)


## 1.0.6

  * Account adding crash on Froyo fixed
  * Secure file deletion
  * Option to delete key file after import
  * Stream encryption/decryption (gallery, etc.)
  * New options (language, force v3 signatures)
  * Interface changes
  * Bugfixes


## 1.0.5

  * German and Italian translation
  * Much smaller package, due to reduced BC sources
  * New preferences GUI
  * Layout adjustment for localization
  * Signature bugfix


## 1.0.4

  * Fixed another crash caused by some SDK bug with query builder


## 1.0.3

  * Fixed crashes during encryption/signing and possibly key export


## 1.0.2

  * Filterable key lists
  * Smarter pre-selection of encryption keys
  * New Intent handling for VIEW and SEND, allows files to be encrypted/decrypted out of file managers
  * Fixes and additional features (key preselection) for K-9 Mail, new beta build available


## 1.0.1

  * GMail account listing was broken in 1.0.0, fixed again


## 1.0.0

  * K-9 Mail integration, APG supporting beta build of K-9 Mail
  * Support of more file managers (including ASTRO)
  * Slovenian translation
  * New database, much faster, less memory usage
  * Defined Intents and content provider for other apps
  * Bugfixes