* Create atleast 10 records using the create method
```ruby 
#<Products:0x0000558f45f019a8
 id: 1,
 name: "Evian",
 description: "Mineral Water",
 quantity: 1,
 price: 250.0,
 available: true,
 released_at: Tue, 01 Oct 2024,
 expiry_date: nil,
 discount: 0.0,
 created_at: Tue, 01 Oct 2024 14:50:55.356573000 UTC +00:00,
 updated_at: Tue, 01 Oct 2024 14:50:55.356573000 UTC +00:00>

#<Products:0x0000558f466b1298
 id: 2,
 name: "Wilkins",
 description: "Distilled Water",
 quantity: 1,
 price: 80.0,
 available: true,
 released_at: Tue, 01 Oct 2024,
 expiry_date: nil,
 discount: 0.0,
 created_at: Tue, 01 Oct 2024 14:59:27.737878000 UTC +00:00,
 updated_at: Tue, 01 Oct 2024 14:59:27.737878000 UTC +00:00>
    
#<Products:0x0000558f46a09f58
id: 3,
name: "Nature Spring",
description: "Drinking Water",
quantity: 1,
price: 25.5,
available: true,
released_at: Tue, 01 Oct 2024, 
expiry_date: nil,
discount: 0.5,
created_at: Tue, 01 Oct 2024 15:04:15.246609000 UTC +00:00,
updated_at: Tue, 01 Oct 2024 15:04:15.246609000 UTC +00:00>

#<Products:0x00007f476488e9f8
id: 4,
name: "Summit",
description: "Purified Water",
quantity: 1,
price: 28.2,
available: true,
released_at: Tue, 01 Oct 2024,
expiry_date: nil,
discount: 10.0,
created_at: Tue, 01 Oct 2024 15:09:44.302172000 UTC +00:00,
updated_at: Tue, 01 Oct 2024 15:09:44.302172000 UTC +00:00>

#<Products:0x0000558f463299b8
id: 5,
name: "Absolute",
description: "Purified Water",
quantity: 25,
price: 1200.0,
available: true,
released_at: Tue, 01 Oct 2024,
expiry_date: nil,
discount: 8.0,
created_at: Tue, 01 Oct 2024 15:12:26.855199000 UTC +00:00,
updated_at: Tue, 01 Oct 2024 15:12:26.855199000 UTC +00:00>

#<Products:0x0000558f466994e0
id: 6,
name: "Pure",
description: "Purified Water",
quantity: 50,
price: 800.0,
available: true,
released_at: Tue, 01 Oct 2024,
expiry_date: nil,
discount: 30.0,
created_at: Tue, 01 Oct 2024 15:16:42.099725000 UTC +00:00,
updated_at: Tue, 01 Oct 2024 15:16:42.099725000 UTC +00:00>

#<Products:0x0000558f46a834e8
id: 7,
name: "Premier",
description: "Distilled Water",
quantity: 100,
price: 2000.0,
available: true,
released_at: Tue, 01 Oct 2024,
expiry_date: nil,
discount: 25.0,
created_at: Tue, 01 Oct 2024 15:22:40.109179000 UTC +00:00,
updated_at: Tue, 01 Oct 2024 15:22:40.109179000 UTC +00:00>

#<Products:0x0000558f45716860
id: 8,
name: "Le Minerale",
description: "Mountain Water",
quantity: 250,
price: 3500.0,
available: true,
released_at: Tue, 01 Oct 2024,
expiry_date: nil,
discount: 0.0,
created_at: Tue, 01 Oct 2024 15:27:21.968887000 UTC +00:00,
updated_at: Tue, 01 Oct 2024 15:27:21.968887000 UTC +00:00>

#<Products:0x0000558f46429de0
id: 9,
name: "Aquafina",
description: "Drinking Water",
quantity: 10,
price: 80.95,
available: false,
released_at: Tue, 01 Oct 2024,
expiry_date: nil,
discount: 0.0,
created_at: Tue, 01 Oct 2024 15:31:43.891162000 UTC +00:00,
updated_at: Tue, 01 Oct 2024 15:31:43.891162000 UTC +00:00>

#<Products:0x0000558f465f19e8
id: 10,
name: "Crystal CLear",
description: "Purified Water",
quantity: 1,
price: 30.0,
available: true,
released_at: Tue, 01 Oct 2024,
expiry_date: nil,
discount: 0.0,
created_at: Tue, 01 Oct 2024 15:32:57.711107000 UTC +00:00,
updated_at: Tue, 01 Oct 2024 15:32:57.711107000 UTC +00:00>
```
* Create atleast 10 records using the save method
```ruby 
product = Products.new
product.name = 'Choco Wacko'
product.description = 'Chocolate Donut'
product.quantity = 10
product.price = 300.5
product.available = true
product.released_at = DateTime.now - 10
product.expiry_date = DateTime.now + 12
product.discount = 0
product.save

product = Products.new
product.name = 'Choco Butternut'
product.description = 'Nutty Donut'
product.quantity = 10
product.price = 300.5
product.available = true
product.released_at = DateTime.now - 4
product.expiry_date = DateTime.now + 9
product.discount = 0
product.save

product = Products.new
product.name = 'Bavarian'
product.description = 'Cream filled'
product.quantity = 15
product.price = 380.00
product.available = true
product.released_at = DateTime.now - 5
product.expiry_date = DateTime.now + 15
product.discount = 20
product.save

product = Products.new
product.name = 'Boston Creme'
product.description = 'Choco filled'
product.quantity = 200
product.price = 1089.00
product.available = false
product.released_at = DateTime.now - 3
product.expiry_date = DateTime.now + 15
product.discount = 50
product.save

product = Products.new
product.name = 'Choco Honey Dipped'
product.description = 'Glazed'
product.quantity = 185
product.price = 2080.00
product.available = true
product.released_at = DateTime.now - 3
product.expiry_date = DateTime.now + 16
product.discount = 15
product.save

product = Products.new
product.name = 'Classic'
product.description = 'Glazed'
product.quantity = 100.00
product.price = 1050.00
product.available = true
product.released_at = DateTime.now - 3
product.expiry_date = DateTime.now + 16
product.discount = 15
product.save

product = Products.new
product.name = 'Blueberry Cheese'
product.description = 'Special'
product.quantity = 1
product.price = 100.00
product.available = true
product.released_at = DateTime.now - 3
product.expiry_date = DateTime.now + 21
product.discount = 0
product.save

product = Products.new
product.name = 'Vanilla'
product.description = 'Glazed'
product.quantity = 1
product.price = 25.00
product.available = true
product.released_at = DateTime.now - 1
product.expiry_date = DateTime.now + 21
product.discount = 5
product.save

product = Products.new
product.name = 'Assorted'
product.description = 'Max flavors'
product.quantity = 12
product.price = 255.00
product.available = true
product.released_at = DateTime.now - 12
product.expiry_date = DateTime.now + 21
product.discount = 5
product.save

product = Products.new
product.name = 'Secret Recipe'
product.description = 'Secret'
product.quantity = 1
product.price = 9999.00
product.available = false
product.released_at = DateTime.now - 12
product.expiry_date = DateTime.now + 21
product.discount = 0
product.save
```
* Fetch all products where name is "Laptop".
```ruby
Products.where(name: 'Laptop')  
```
* Fetch all products where price is greater than 100.
```ruby
Products.where('price > ?', 100)
```
* Retrieve products where available is true.
```ruby
Products.where(available: true)
```
* Fetch products where quantity is less than 50.
```ruby
Products.where('quantity < ?', 50)
```
* Find products where discount is exactly 10%.
```ruby
Products.where('discount =?', 10)
```
* Retrieve products where name contains the word "Pro".
```ruby
Products.where('name LIKE ?', '%Pro%')
```
* Fetch products where description includes the word "portable".
```ruby
Products.where(description: 'portable')
```
Find products where price is between 50 and 150.
```ruby
Products.where(price: 50..150)
```
* Retrieve products where available is false and quantity is greater than 0.
```ruby
Products.where(available: false).and(Products.where("quantity > '0'"))
```
* Fetch products where released_at is after January 1, 2023.
```ruby
Products.where('released_at > ?', Date.new(2023, 1, 1))
```
* Find products where expiry_date is nil.
```ruby
Products.where(expiry_date: nil)
```
* Retrieve products where released_at is before January 1, 2022
```ruby
Products.where('released_at < ?', Date.new(2022, 1, 1))
```
* Fetch products where quantity is between 10 and 100.
```ruby
Products.where(quantity: 10..100)
```
* Find products where discount is greater than or equal to 5%.
```ruby
Products.where('discount >= ?', 5)
```
* Retrieve products where price is less than or equal to 200 and available is true.
```ruby
Products.where('price <= ?', 200).and(Products.where(available: true))
```