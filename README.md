# paywithm-pesa
make your payment 
from intasend import APIService

publishable_key = "INTASEND_PUBLISHABLE_KEY"

service = APIService(publishable_key=publishable_key)

response = service.collect.mpesa_stk_push(phone_number=2547...,
                                  email="joe@doe.com", amount=10, narrative="Purchase")
print(response)