# Christopher Carter

### Chess Boxing

I personally am not big into sports, and so I chose one that I just think is cool. I think chess boxing is cool because it combines chess a game thats very much about logic and **mental prowess** and boxing which is more about brawn and **physical prowess**. While not a popular sport I think it should be just because of how unique of a combination it is. To win someone either must knockout their opponent in boxing or must checkmate them in chess.

----------------------
## Mogul Chessboxing Championship Chessboxers
1. DisguisedToast
2. Myth
3. PointCrow

* Dynamix MMA in Santa Monica
* Gleason's Gym in Brooklyn
* Any gym with a boxing ring that would allow it

[Link to MyDish](MyDish.md)

-----------------------
## Food Places
| Food Place | Description | Location |
| --- | --- | --- |
| McDonalds | Fast food burger franchise | found around the world |
| Mi Casa | Mexican restaurant | found in Kirksville Missouri |
| Chick-fil-A | Go to place for all things chicken | found in the US and a few other countries |
| Taco Bell | Fast food taco franchise | found throughout the world|

-----------------------
## Jokey Quotes
> "I would say don't take advice from people like me who have gotten very lucky. We're very biased. You know, like Taylor Swift telling you to follow your dreams is like a lottery winner telling you, 'Liquidize your assets; buy Powerball tickets - it works!'"
-Bo Burnham

> "I fully embrace myself as a hypocrite."
-Bo Burnham

-----------------------
## Code Fencing
The following code creates a singleton class structure in Dart which ensures only one instance of a class is created. [Third snippet on this link](https://code.pieces.app/collections/dart)
~~~
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
~~~