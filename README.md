# binary39
index of bip39 words list with binary indexes

the file index.html generates a bip39 words list with both binary and decimal indexes.
the page can be saved as pdf with a browser and printed to create your own bip39 23 words seed flipping a coin 11 times per word and checking the corresponding word in the binary index.

the file index.html contains the bip39 words list hardcoded! this means this file will work the same forever! However some users could not trust the hardcoded list and they would like to verify only the code and not the words list. So the file index_dynamic_words.html instead fetch the data from https://raw.githubusercontent.com/bitcoin/bips/master/bip-0039/english.txt dynamically on each refresh and you don't have to trust any hardcoded list, just verify the code. If the contents of that github link change, index_dynamic_words.html won't produce the same output forever though! You can even use both and compare results!
