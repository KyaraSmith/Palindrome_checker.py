def is_palindrome(word):
    word = word.lower()  # convert the word to lowercase
    reversed_word = word[::-1]  # reverse the word
    if word == reversed_word:  # check if the original and reversed words are the same
        return True
    else:
        return False
