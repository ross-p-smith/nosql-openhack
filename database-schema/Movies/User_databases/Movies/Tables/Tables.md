#### 

[Movies](../index.md) > Tables

# ![Tables](../../../Images/Table32.png) Tables

---

## <a name="#objects"></a>Objects

| Name | Description |
|---|---|
| [dbo.Associations](Associations.md) | _Experimental: Used for associating movies for recommendations. Generated by custom ML model._ |
| [dbo.Cartitem](Cartitem.md) | _Movies added to a user's cart._ |
| [dbo.Category](Category.md) | _Movie categories._ |
| [dbo.Event](Event.md) | _Experimental: User clickstream events, such as browsing and adding items to a cart._ |
| [dbo.Item](Item.md) | _Movie items. NOTE: Ignore the aggregate columns here ;)_ |
| [dbo.ItemAggregate](ItemAggregate.md) | _Experimental: Aggregates, such as buy count, view details count, add item to cart count, and vote count. Ignore the other fields._ |
| [dbo.ItemCategory](ItemCategory.md) | _Mapping between items and categories. There should be a relationship between this table and the Category table..._ |
| [dbo.OrderDetails](OrderDetails.md) | _All details related to placed orders._ |
| [dbo.Orders](Orders.md) | _Placed orders._ |
| [dbo.Ratings](Ratings.md) | _Movie ratings for each user._ |
| [dbo.Similarity](Similarity.md) | _Experimental: Similarity between movies, generated by custom ML model._ |
| [dbo.User](User.md) | _All user accounts._ |


---

###### Author:  Contoso Movies, Ltd.

###### Copyright 2019 - All Rights Reserved

###### Created: 2019/11/27
