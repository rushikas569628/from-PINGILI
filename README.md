# from-PINGILI
markdown topic
# RUSHIKA
###### Rooftop restaurant
I like **Ambience** and when it comes to **food** egg noodles is my favorite

---

### Favourite dishes:
1. Egg fried Rice
2. Biryani
3. chowmein

### Places to visit near Restaurant:
* Park
* library
* Galleria Showroom

Link to mymedia: ![MyMedia](MyMedia.md)

---

# TedX Talks
###### I frequently watch tedx talks and they are my go-to videos.If I had to recommend someone to try I would tell them to watch below 4 videos:

 |Title of Video|Reason|Creator Name|
 |---|---|---|
 |It is okay not to have a plan|It's about passion and learning along the way|Mithila Palkar|
 |Live for yourself|Need to love yourself before loving others as none of those very people are gonna pay your bills, thus eradicating the need to impress others|Chetan Bhagat|
 |Faith is not always blind|The essence of family relations,her love for arts and the trust we should put in each other as a family and how that helps a family grow.|Geetha Bhascker|
 |To Ace LIMITLESS|Ideas of Governanceideas of good governance can be implemented to make the society gravitate towards better and corruption free society by erasing the limiting beliefs|Rohini Sindhuri|

 ---

 # Quotes

 “Many a times there is no perfect solution for a given problem. No solution is also a solution. Everything depends upon how you look at it. We make judgements on others depending upon what we think of them.”
— *Sudha Murty*

"Be yourself; everyone else is already taken.”
― *Oscar Wilde*

---

## Code Fencing

Finding intersection of lists using Dart-9

<https://code.pieces.app/collections/dart>

```
main() {
  final lists = [
    [1, 2, 3, 55, 7, 99, 21],
    [1, 4, 7, 65, 99, 20, 21],
    [0, 2, 6, 7, 21, 99, 26]
  ];

  final commonElements =
      lists.fold(
        lists.first.toSet(), 
        (a, b) => a.intersection(b.toSet()));

  print(commonElements);
}


```