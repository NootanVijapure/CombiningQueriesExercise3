**Exercise 1: Identifying Commonly Purchased Products**

Suppose you are given three tables: **customers**, **products\_purchased**, and **products**. Customers make purchases from different cities, and you want to identify products that are purchased by customers in both New York and San Francisco.

Customers:

| customer\_id | name | city |

|-------------|---------|----------------|

| 1 | Alice | New York |

| 2 | Bob | New York |

| 3 | Charlie | New York |

| 4 | David | San Francisco |

| 5 | Eve | San Francisco |

Products Purchased:

| customer\_id | product\_id |

|-------------|------------|

| 1 | 1 |

| 1 | 2 |

| 2 | 2 |

| 3 | 1 |

| 4 | 3 |

| 5 | 3 |

| 5 | 4 |

Products:

| product\_id | product\_name |

|------------|--------------|

| 1 | Laptop |

| 2 | Headphones |

| 3 | Smartphone |

| 4 | Tablet |

**Exercise 2: Customers Who Purchased in NYC But Not in SF**

Now, you want to find out customers who made purchases in New York but not in San Francisco.

**Exercise 3: Union of All Purchased Products**

Lastly, you need to get a list of all unique products purchased by customers in either New York or San Francisco.
