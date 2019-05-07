# hw9

## 1、领域建模：

1. 根据定旅馆建模文档：

  - 对Make Reservation 用例开展领域建模

    ![week9_make reservation](.\Pictures\week9_make reservation.png)

- 数据建模

	Hotel(name,star,addr,loc id,brief intro,favorite,price,rating,max-discount-off)

	Room(type,date,isAvailable,reserved,price,reserved num,total num)

	RoomDesc(type,totals,list-price,discount,total num,description)

	Room Catalog(type)

	ReservationItem(type,adults,children,chid-age)

	Reservation(check in date,check out date,number of nights)

	traveler(name,email)

- 对payment 用例开展领域建模

  ![week9_payment](.\Pictures\week9_payment.png)
  
  - 数据建模
  
  	Reservation(rooms, check in date,check out date)
  
  	customer(name,address,city,country,postcode,tel)
  
  	payment(item details, total price)
  
  	credit card(type, bank, number, security code, expiry date)

2. 使用 UML State Model，对每个订单对象生命周期建模

	![week9_lifecycle](.\Pictures\week9_lifecycle.png)
