# CollapseToolbar

How to implement a collapsing toolbar with an expandable image into our Android app.
For this, we have to wrap a CollapsingToolbarLayout that contains a Toolbar and an ImageView into an AppBarLayout. The AppBarLayout, on the other hand, has to be placed inside a CoordinatorLayout in order to allow its child views to react to scroll events. Scrolling is synchronized via the layout_behavior and layout_scrollFlags attributes. Available scroll flags are scroll, exitUntilCollapsed, enterAlways, enterAlwaysCollapsed, snap, and snapMargins. This layout works in combination with scrollable views like RecyclerView or NestedScrollView. All widgets are available through the Material Components library.
