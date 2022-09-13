# GroceryApplication
project for android development using kotlin -grocery Application

I am Thavva Aiswarya Lakshmi-I have build grocerry app so taht there will be no problems in remembering the items or grocerries that we want to purchase while going to a grocer shop
 ------------
 ------------
 -> At the very first I have wrote all the dependencies that are required to make the app
 ->I have added the colors that i want for the Layout of the app,I have used all purple and blue combinations.
 ->in values->themes I have created themes
 ->in java created grocery dao class to perform several operations like insert , delete
                ->created grocery Items to give ->itemname
                                                ->itemsize
                                                ->item cost
->created database class for our database 
->create repository class and specify insrt delete functions again
->create view model factory class
after writing its functionalities
------------
------------
->open main activity
          ->we specify layout,background and other interface settings
          ->add icons
          ->initialising variables with id's
->in layout file
             ->adding textview,card type,layout height width etc
             ->add delete icon
 ->create adapter class for recycling items
            ->set view for each item,and listeners for buttons etc
  ->for open dialog box create separate dialog box with card layout
             ->add layout width ,height,orientation,sum ,margin etc for every item specified
   ->add custom background->drawable->custom buttom
              ->opt necessary modification like color,radius etc
   ->add logo for our application->go to manifest ->change icon code
   after careful checkings
   ------------
   ------------
   grocerry app is successfully build
   ->where we can add grocer items ,quantity,price 
   ->can also deleted items
