# International-base-cost-applied


international_shipping = True


total = 149

shipping_cost = 12

if international_shipping:

    shipping_cost += 15
    
    print("International base cost applied")
    
    
if total <= 50:

    shipping_cost += 20
    
    
elif total <= 100:

    shipping_cost += 15
    
    
else:

    shipping_cost += 5


print(f'shipping cost: {shipping_cost}')
