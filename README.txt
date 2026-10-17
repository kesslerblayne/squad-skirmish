SQUAD SIM - installable app package

Files (keep them all together in the same folder):
  index.html           the game
  manifest.webmanifest tells the phone how to install it
  sw.js                lets it work offline
  icon-192.png, icon-512.png, apple-touch-icon.png   app icons

To use it: put these files on any free web host (see the steps in the chat), open the
address in Safari on your iPhone, tap Share, then "Add to Home Screen".

Updating later: replace index.html on the host. In sw.js change VERSION to a new
name (for example squad-sim-v2) so installed copies refresh.

IMPORTANT: saves live inside the browser at one specific web address. A new address
starts empty. Before moving, use Manage > Universe settings > Backup ALL universes at the
old address, then Restore backup at the new one.
