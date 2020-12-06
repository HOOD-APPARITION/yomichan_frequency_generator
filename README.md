Script that takes in a tab seperated frequency list (such as the output from certain analyzers using kuromoji or mecab) and outputs a frequency list that can be read by yomichan.

Tested with morphman readability analyzer (use word_freq_report.txt, not frequency.txt) and [Wareya's analyzer](https://github.com/wareya/analyzer).

Usage:
python yomichan_frequency_generator.py -i NAME_OF_FREQ_LIST -title TITLE

Optional: -occurence  Shows the total of occurences of each given word instead of the rank within the frequency list.
