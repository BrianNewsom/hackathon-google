# Team Members

* [Adrian Chen](github.com/adrian-chen)
* [Brian Newsom](github.com/briannewsom)
* [Ian Ker-seyemer](github.com/ianks)
* [Jake White](github.com/jakewhite8)
* [Mike Fyk](github.com/thefyk)

# Objective 1. Analysis

## Finding 1

![visualization](viz.png) or {{ query/result }}

```js
db.google.find().sort({“rankingInfo.absoluteScore” : 1}).limit(10)
```
```json


{ “_id” : ObjectId(“548649dcd23e3ff8aa754362”), “id” : “986695912626”, “name” : “the little memory”, “productId” : “honmnihjmiioifehpiepkldneddleedn”, “primaryMimeTypes” : [ “application/vnd.google-apps.drive-sdk.986695912626” ] }
{ “_id” : ObjectId(“548649dcd23e3ff8aa75436d”), “id” : “694729839641”, “name” : “Pixeffect - Photo Effects”, “productId” : “koekplodmdaalggcclajcecoomipnpca”, “primaryMimeTypes” : [ “application/vnd.google-apps.drive-sdk.694729839641” ] }
{ “_id” : ObjectId(“548649dcd23e3ff8aa754373”), “id” : “860115892612”, “name” : “Video Player”, “productId” : “gdebnehfojpoccpaocfbelbclfnpbmij”, “primaryMimeTypes” : [ “application/vnd.google-apps.drive-sdk.860115892612” ] }
{ “_id” : ObjectId(“548649dcd23e3ff8aa75437e”), “id” : “367378856688”, “name” : “Freshdesk”, “productId” : “kkgpfcbanbnipdjijjaljkhhlhaiehpo”, “primaryMimeTypes” : [ “application/vnd.google-apps.drive-sdk.367378856688” ] }
{ “_id” : ObjectId(“548649dcd23e3ff8aa754383”), “id” : “870861426174”, “name” : “Speed Test”, “productId” : “dhhjlgjphgjlijjbilomfnohfnljllmo”, “primaryMimeTypes” : [ “application/vnd.google-apps.drive-sdk.870861426174” ] }
{ “_id” : ObjectId(“548649dcd23e3ff8aa754390”), “id” : “921361231662”, “name” : “Perfode-eReviewz”, “productId” : “ccppkjnmkhogdldnimkfehmmoobbkkki”, “primaryMimeTypes” : [ “application/vnd.google-apps.drive-sdk.921361231662” ] }
{ “_id” : ObjectId(“548649dcd23e3ff8aa754392”), “id” : “80838847420”, “name” : “Kwikkel”, “productId” : “icnfhnnhhfkbliceililbacjeapdkjmf”, “primaryMimeTypes” : [ “application/vnd.google-apps.drive-sdk.80838847420” ] }
{ “_id” : ObjectId(“548649dcd23e3ff8aa754395”), “id” : “371192490008”, “name” : “Livezhat”, “productId” : “bbonmlaliiekiobamaaloacochgbhmho”, “primaryMimeTypes” : [ “application/vnd.google-apps.drive-sdk.371192490008” ] }
{ “_id” : ObjectId(“548649dcd23e3ff8aa7543bb”), “id” : “713371029155”, “name” : “FileThis”, “productId” : “kbllbadpemgdidoajfihnijjpeljkofn”, “primaryMimeTypes” : [ “application/vnd.google-apps.drive-sdk.713371029155” ] }
{ “_id” : ObjectId(“548649dcd23e3ff8aa7543c1”), “id” : “803229865151”, “name” : “Weavr”, “productId” : “pleickehbpekbickneiciemijnackeih”, “primaryMimeTypes” : [ “application/vnd.google-apps.drive-sdk.803229865151” ] }
```

This lists the most highly rated apps in the dataset, and their relevant data.  We see certain niches that already have popular, well
received apps.  This is good to know so we don’t create something that’s already done well.

## Finding 2

![visualization](viz.png) or {{ query/result }}

{{ discussion }}

## Finding (add more if necessary)

# Objective 2. Data App

## Mockup 

Our idea is a notification app that notifies you when changes are made to a file in drive. This tool would be best utilized as a chrome extension or google now.
Key features:
* Links to Hangouts and the drive document

Stretch goals:
* Create an application that is integrated more closely with other word processing programs (VIM)
* Machine learning to discern the idea behind the change

## Use cases 


## API uses 

(specific Google APIs you will need to use to make the app)

## Implementation plan 

(how your team would build this app if given sufficient time)

