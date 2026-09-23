# Soil Moisture Reader

```package
kitronik-smart-greenhouse
```

## Step 1 @showdialog

In this tutorial you will set up the micro:bit to read the soil moisture sensor and display the reading on the LED screen.

## Step 2

Go to ``||Variables:Variables||`` and click **Make a Variable**. Name it **Soil Moisture**.

## Step 3

In ``||basic:on start||`` add ``||variables:set Soil Moisture to 0||``.

## Step 4

Add a ``||basic:forever||`` loop. Inside it set **Soil Moisture** to **soil prong moisture** from the Kitronik FarmBeats blocks.

## Step 5

Add ``||basic:show number||`` and drop in the **Soil Moisture** variable.

## Step 6

Add ``||basic:pause (ms) 500||`` then ``||basic:clear screen||`` then ``||basic:pause (ms) 5000||``.

## Step 7 @showdialog

Download your code and test it with the soil sensor!
