### Story 1
-Accept input of word that begins with a vowel
  this already works
  
-Click submit button
  this already works

-Can see words that begin with vowel, translated to pig latin ('way')
  check the first index of `eachWord` -> `eachWord[0]`
  if vowelsArray contains `eachWord[0]`
  add `way` to the end of `eachWord`
  return the result
  
  ### Story 2
  - Can type any word that has a "qu" in the first syllable in the text input (e.g. squeal)
      Already works
      
  - Can hit the submit button
      Already works
  
  
  - Can see the words that have a "qu" in the first syllable translated to Pig Latin and rendered to the page (e.g. ealsquay)
  - squeal -> ealsqu -> ealsquay
  - run a 'for' loop
  - s | queal -> check to see if letter is a vowel
      if yes, return the word
      if no, then re-slice the word with first 2 letters: sq | ueal
      if first slice contains 'qu' before we hit a vowel
        move letters to the end of the word and add 'ay'
        
### Story 3

