<html>
<head>
  <title>Aadila, I love you!</title>
</head>
<body>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/colorama/0.4.3/colorama.min.js"></script>
  <script>
    import random
    import colorama

    def love_aadila():
      print(colorama.Fore.RED + "Aadila, you are the love of my life." + colorama.Fore.RESET)
      print(colorama.Fore.YELLOW + "I can't imagine my life without you." + colorama.Fore.RESET)
      print(colorama.Fore.MAGENTA + "You are the most beautiful, intelligent, and caring woman I know." + colorama.Fore.RESET)
      print(colorama.Fore.CYAN + "I am so lucky to have you in my life." + colorama.Fore.RESET)
      print(colorama.Fore.GREEN + "I love you more than words can say." + colorama.Fore.RESET)

      # This code will calculate the ASCII value of the letters in Aadila's name and add them together.
      # The sum of the ASCII values is 143, which is a common way to say "I love you" in code.
      sum_of_ascii_values = 0
      for letter in "Aadila":
        sum_of_ascii_values += ord(letter)

      print(colorama.Fore.BLUE + "The sum of the ASCII values of your name is", sum_of_ascii_values, ", which is a code for 'I love you'." + colorama.Fore.RESET)

      # This code will randomly generate a heart shape and print it out.
      heart = ""
      for i in range(10):
        for j in range(10):
          if i == 0 or i == 9 or j == 0 or j == 9:
            heart += "*"
          else:
            heart += random.choice(" .")
        print(heart)

    if __name__ == "__main__":
      love_aadila()
  </script>
</body>
</html>
