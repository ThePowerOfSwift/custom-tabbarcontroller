# custom-tabbarcontroller


## How to set top left and right corner radius with desired drop shadow in UITabBar ?



![alt text](https://github.com/Ghazzway/custom-tabbarcontroller/blob/master/image/Screen%20Shot%202.png
 "TabBar image")
 
 


***


## Steps

1. Add a coustmeTabBarView.
  *  Add the cornerRadius to coustmeTabBarView.
  *  Add the shadow to coustmeTabBarView.
2. In  viewDidLayoutSubviews  make the coustmeTabBarView frame equal to tabBar frame.
  *   In viewDidAppear Adjust the safe area to the height of the bottom views.
  *   In viewDidAppear  Adjust the safe area insets of the embedded child view controller .
3.   Add  private func with name addcoustmeTabBarView . 
  *   In addcoustmeTabBarView make the coustmeTabBarView frame equal to tabBar frame.
  *   In addcoustmeTabBarView addSubview coustmeTabBarView to view.
  *   In addcoustmeTabBarView  bringSubviewToFront  tabBar to view.

4. Add func hideTabBarBorder (optional).
  *   In  hideTabBarBorder  make the tabBar background Image &  tabBar shadowImage  to empty image .
  *   In  hideTabBarBorder make tabBar clipsToBounds = true.
  
  5. Add func addcoustmeTabBarView & hideTabBarBorder to viewDidLoad
  





