# DZ_40
def buy_products(*args):
    products = {}
    for item in args:
        products[item[0]] = item[1]
    return products
