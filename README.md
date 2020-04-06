# Lockdown Essential services

Lockdown Essential services allows people to,

1. Book slots for travel for essential services during lockdown

2. Act as a distribution platform of essential service during lockdown

# Motivation

We have seen a lot of cases of clashes between people and the police
during the lockdown due to COVID19 spread. Heated arguments and
sometimes even physical assault, in places this has even led to the
death of the people involved. This happens due to the confusion
created by the tense situation.

We plan in creating a system, which can,

## 1. Book slots for travel for essential services during lockdown

a) Where government agencies will be able to access and
administrator interface for areas and approve travel request by
people, based on the description time, relevancy of the travel request
and travel history.

b) Where the common people will be able to sign up and create
travel requests for the next day or the next slot. This can facilitate
smoother public movement in this lockdown, without creating panic, and
also avoiding physical contact at the checkposts, which is otherwise a
fertile land for COVID19 spread.

## 2. Act as a distribution platform of essential service during lockdown

a) There may be certain areas in the country where total restriction
in movement has to be imposed. But at the same time distribution of
food, medicine has to still go on at a time when civilians have
restrictions in movement.

b) With the app people will be able to place requests for food,
grocery, milk and medicinal supplies. This information will be
aggregated by residents associations or local administration, which
then can take adequate action to distribute goods and services to
houses of the people. This may be done contactlessly.

// # Getting started
 // ## Installing

// A step by step series of examples that tell you how to get a
// development env running 

//Say what the step will be

#  Description

**1.   Start with breaking the whole process into four categories, and specifications needed at each stage. 
      The four categories are:**
      - Consumer
      - Delivery person
      - Shops
      - Government & police
      
**2. Starting with the consumer, our app would have to focus on:**
  * **a) Specification of goods:** We are currently focusing on essential foods (rice, grains, pulses, vegetables, fruits,        milk, sugar, oil, salt and few masalas), and medical needs (very especially for life threatening needs, masks, sanitizers,bandages), few essentials( soap, etc).
  
 * **b) Brands being offered:** This we will have to mention along with the shops who are willing to offer them, and show as such in the app, with price.
 
 * **c) Payment method (mostly digital payment) and how will we ensure and keep record of transactions (proper DBMS):** We need to make at least 3-4 options available and take care of any procedure needed for the same. Though direct payment sounds good, if there is a middleman (delivery), how is his cut? For cash payments, ensure both parties are informed to wear mask, and change needs to be kept ready.
 
* **d) What all are the shops that will be available, or is it just a random collection of items which consumers pick, and the delivery person has to run around to get (not a great idea):** Shops are a good idea to contact, but then again contacting will need to be taken care of.

*  **e) Specification of delivery areas:** Where all will the services be available (so good idea to ask for location or access it, and then offer the rest of the service).

*  **f) Time slots:** Take into account best slots, and maximum number of orders per delivery person.. So 2 slots, in the morning and evening, alternate days and 5 orders max for each.

*  **g) User ID or group ID:** Registering of customers for easier handling and storing of transactions (but more data to handle..) And in the case of pooling orders, how will we be grouping areas? apartments wise, area wise, and how to make people aware of which groups they can pool with, and how will each person's order be distinguished by the seller in the group?

*  **h) Delivery option:** Drop at the door, or collect from the person (the delivery person can call the person instead ringing doorbells)

*  **i) Accessibility of app:** How will this app reach people: Play store, SMS link (that means considering mobile network charge). Also a proper trial of the app must be done. 

*  **j)** It must be easy to use, making an option for **elderly or digitally illiterate people** (such as call and order maybe..) would be cool, again location needs to be correctly got.

*  **k)** We can keep in mind, if possible can the **app be used for the future?**.. 

*  **l)** We could think of expansion for **cooked food distribution, or gas service?**
  
**3. Our second stage is the delivery person:** 
 * **a) Selection:** Will there be an outside delivery person, or we can give an option for someone to volunteer to collect the items (which can be made ready at the store). If it is the volunteer option, how will the pass be given?
 
 * **b) Safety measures:** During handling of the items, ensuring a sanitizer at all times, and if possible a mask. 
 
 * **c) Mode of transport:** Bike would be sufficient for single orders, but in case pooling and since it is five orders, they might need a bigger transport (car possibly..)
 
 * **d) Range of each delivery person:** What is the radius that each person willbe working in, (in sqkm)
 
 * **e) How many delivery people** in an area would be needed?
 
 * **f) Payment:** In the case of a delivery person, what is his commission? 
 
 * **g) How will the slots be divided and how many people per slot (depending on the pass)**
 
 * **h)** How to **ensure no miscommunication** at any end.. And ensuring any updates reflect for all parties. 
 
 * **i) A pass check before anyone goes on the road**
 
 * **j) COVID affected neighbourhoods must be marked** so, so as to avoid any infection and safe delivery of items
  
 **4. Our third stage, shops:**
  * **a) Contact:** Which shops are we planning to contact, is it a chain? (maybe easier, if we get contacts) or nearby shops.. Government is distributing ration, will we be taking that also for delivery? and also medical shops. 
  
  * **b) Collecting a list of products and the brands given by the store, consolidating a list shopwise as well as brand wise maybe (if we are going to offer) , and providing filters like sorting according to type of items, shops,etc.**
  
  * **c) How will the shops receive the order, the format and location, and again ange of area for which they will accept**.Pooled orders must be taken care of, as the seperate lists must appear so ( for seperate packaging, jute sacks maybe). 
  
  * **d) If we are taking into consideration farmer produce, how will we connect the farmer and end consumer..** ?
  
  * **e) Ensuring correct transactions and amount at both ends**, also running a trial will help us check the availability of goods and minimum quality. 
   
 **4) Fourth and most important is the government:**
   We need to get permission and passes for slots for those areas, to ensure proper functioning. We can use admin help, after showing material results, and running a small trial. 
  
  *All work, can be divided and started parallely, especially contacting government and people.
   


```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it
for a little demo

## 

# Contributors / Author

*Add your name at end*

1. Dr. Anoop Jacob Thomas, Assistant Professor, Department of Computer
Science and Engineering, Indian Institute of Information Technology
Tiruchirappalli
