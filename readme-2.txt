Our work is to make a better stemming tool for bangla words. Already there is a python 
library to do this job. But they have some lackings too. We have aimed to overcome these 
problems and design our very own models with new training tehnique. This work has been 
performed in many steps as follow- 
1.Firstly we identify the possible pattern of bengali words that may be reduced to its root 
 word also known as stemming.
2. We have found that the most common patterns are "বিভক্তি" and "বচন" .
3. Generally these patterns are sit after words as postfix.
4. Then we have checked the stemmed word is valid or not.
5. The checking task is done with the help of a dictionary that is developped by our ourself
   using our previous news dataset.
6. We also try to scrap word from traditional bangla academy dictionary, but the amount of word
   was not satisfied for our model.
7. Finally we compare our output with a python library(bangla-stemmer 1.0) output.

 
**********************Comparision Of Outputs********************************

main-  bangla-     our-
word   stemmer     stemmer

কুমার --> কুম -->কুমার
শেয়ারবাজার --> শেয়ারব -->শেয়ারবাজার
থেকে --> থেক -->থেক
টাকা --> টাকা -->টাকা
উত্তোলনে --> উত্তোলনে -->উত্তোলন
প্রিমিয়াম --> প্রিমিয়াম -->প্রিমিয়াম
চাওয়া --> চাওয়া -->চাওয়া
কোম্পানিগুলোর --> কোম্পানি -->কোম্পানি
ক্ষেত্রে --> ক্ষেত্রে -->ক্ষেত্র
বুক --> বুক -->বুক
বিল্ডিং --> বিল্ডিং -->বিল্ডিং
পদ্ধতি --> পদ্ধতি -->পদ্ধতি
বাধ্যতামূলক --> বাধ্যতামূলক -->বাধ্যতামূলক
করে --> করে -->কর
সালের --> সাল -->সাল
ডিসেম্বরে --> ডিসেম্বরে -->ডিসেম্বর
পাবলিক --> পাবলিক -->পাবলিক
ইস্যু --> ইস্যু -->ইস্যু
রুলস --> রুলস -->রুলস
জারি --> জারি -->জারি
করা --> কর -->করা
হয়েছে --> হয় -->হয়েছ