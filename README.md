# TODO

- Determine proper error type to throw (e.g., for when passed something that isn't a file)
- Figure out how to get errors to the listener.
- Properly handle pre-existing partial line when watcher first starts
- Make a behaviour rule for if the file shrinks
  - Don't start returning lines until it reaches the previous maximum length?
  - Start returning lines when the file starts growing again? (Prolly that.)
- Make encoding an option?