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
Singleton class structure in Dart to ensure only one instance of a class is created.
<https://code.pieces.app/collections/dart>
```
class SingletonClass {
  static final SingletonClass _instance = SingletonClass._internal();

  factory SingletonClass() {
    return _instance;
  }

  SingletonClass._internal();

  String property1 = 'Default Property 1';
  String property2 = 'Default Property 2';
}

/// Example consuming the singleton class and accessing/manipulating properties
/// To evaluate the difference between a normal class and a singleton class, comment
/// out the factory constructor and _instance in SingletonClass and re-run.
void main() {
  /// Properties before
  String property1Before = SingletonClass().property1;
  String property2Before = SingletonClass().property2;

  print('property1Before: $property1Before'); // Default Property 1
  print('property2Before: $property2Before'); // Default Property 2

  /// Updating the properties
  SingletonClass().property1 = 'Updated Property 1';
  SingletonClass().property2 = 'Updated Property 2';

  /// Properties after
  print('property1After: ${SingletonClass().property1}'); // Updated Property 1
  print('property2After: ${SingletonClass().property2}'); // Updated Property 2
}
```