VVSpringCollectionViewFlowLayout
================================

A spring-like collection view layout. The same effect like iOS7's Message.app.

![demo](https://raw.github.com/onevcat/VVSpringCollectionViewFlowLayout/master/spring-collection-view-over-ios7.gif)

Copy files under `VVSpringCollectionViewFlowLayout` to your project and then init or set a collection view with `VVSpringCollectionViewFlowLayout` instance. 

```objc
VVSpringCollectionViewFlowLayout *layout = [[VVSpringCollectionViewFlowLayout alloc] init];
UICollectionView *collectionView = [[UICollectionView alloc] initWithFrame:self.view.frame collectionViewLayout:layout];
```

See more in the demo.

This project is for my blog post: [http://onevcat.com/2013/09/spring-list-like-ios7-message](http://onevcat.com/2013/09/spring-list-like-ios7-message)
