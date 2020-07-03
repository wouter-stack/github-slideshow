# I am gonna share some code from analytical appication in SAC
## This comes from the button Add Account
```
var productmembers = SALESPLAN.getMembers("SAP_ALL_PRODUCT");
Var_Prod_id = Converters.createStringArr_id(productmembers, "ok");
Var_Prod_descr = Converters.createStringArr_descr(productmembers, "ok");

Popup_new_product.open(); 
```

