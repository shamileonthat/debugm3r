# What is Debug3r
Sh1mmer modifed to be used for exclusively for debugging / messing around on unenrolled / personal.

# Name one reason for why this deserves to exist
It doesn't. It's an hobby project for me to learn how to mess with RMA shims. But back to the request, in school / I.T enviroments where you are learning about chromebooks (for some reason) and said enviroment wouldn't want students using an exploit in the payloads menu to unenroll.

# Isn't this sh1mmer in an new coat of paint
Yep... I'm an skid make fun of me I guess.

# How to build
This will detail instructions on how to build debugm3r as using the developer sh1mmer shim.
First off get your shim for your board from cros.download and chromebrew-dev.tar.gz from https://dl.crosbreaker.dev/chromebrew
Then clone this repo and cd into the wax directory inside of the repo, then run
`sudo bash wax.sh -i shim.bin --chromebrew chromebrew-dev.tar.gz -s 7G -p legacy`

If you want an normal non dev shim with chromebrew do

`sudo bash wax.sh -i shim.binn --chromebrew chromebrew.tar.gz -s 4G -p legacy`
And if you just want an normal shim use
`sudo bash wax.sh -i shim.bin -p legacy`
BTW sh1mmer modern (sh1mmer with the gui) is unsupported
#  Credits
Mercury Workshop: Sh1mmer
supported
