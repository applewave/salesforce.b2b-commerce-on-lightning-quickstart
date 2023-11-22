No	Name	Type	내용	
1	Getting Started with Salesforce B2B Commerce	Commerce	Scratch Org	"sfdx force:org:create
sfdx force:org:open
create setup store.sh
 Create Store
 Create user & buyer user
 Create Search Index
"
2	Salesforce B2B Commerce Workspace Explained	Commerce	Workspaces 소개 (Categoy, Product, Search, Administrat, Account)	"Experence Builder
Categories
Adding Products (Simple, Variation Parent, Entitlement Policy)
Search
Administration (Buyer Access, Store Inventory, Tax Calcaulation, Price Check, Card Payment Gateway, Checkout Flow)
Account ( Buyer, Contact Point Address, Contact, User, Permission Set )"
3	How to setup product visibility in B2B Commerce	Product	Buyer Groups, Entitlements, Price book	"Buyer Tiers (Incentivize tier utilization, Silver, Gold, Platinum )
Buyer Specific ( Maximize Profit )
Product Specific ( Restrict access based on contract - 권한 Access 기반 )

Platnium Buyers
Buyer Group Members (Jil's Outdoor Adventure, Reno Renovatino ) 
- Platnium Buyer Group 
- ( Platnium Pricebook, Platnium Entitlement Policy)

Gold Buyers
Buyer Group Members (Tiny Home Accessories, Fred's Rentals ) 
- Gold Buyer Group 
- ( Gold Pricebook, Gold Entitlement Policy)

Customer Workspace
Customers ( Account, Buyer Group )
Buyer Group
 - Store

Pricing Workspace
 - PriceBook
 - PriceBook Entries"
4	Branding your experence cloud storefront	Front	Theme, Logo, Components, Cart, Navigation, Product, Checkout	
5	Storefront User Creation Flow	User	Contact, User Create	
6	Creating Parent Products with Commerce Cloud	Product	Product Variations, Product Class : Variation Parent	"Simple Product
- Categories
- Entitlements
- Pricebook Entries

Parent Product
- Categories
- Entitlements
Child Product
- Entitlements
- Pricebook Entries

Commerce Setup
- Product Attribute
- Variation Attribute Sets
- Create Product variation

- Searchable Fields
- Results Filters
- Variation attributes translated
"
7	B2B Commerce Integration Adapters	Checkout	Administration (Store Inventory )	
8	Import Porducts into Commerce Cloud	Product	Product Import	"Manully
Data Loader ?
Import Wizard
Workbench

Porduct2
 - Pricebook Entries
 - Product Category Product
 - Commerce Entitlement Product

Parent Product Data
Product2 (Shirt)
 - Product Attribute Set Product (Size-Color)
 Product2 (Shirt-Small)
 - Product Attribute

Import Wizard

Workbench
 - Product2
 - Pricebooks
 - CommerceEntitlmentProduct
 - ProductCategoryProduct"
9	Sneak Peek! Unified Checkout	Checkout	Checkout 화면	
10	Community SEO Best Practices	Commerce	SEO	
11	Customizing Checkout in B2B Commerce	Checkout	Cart, Checkout	
12	Salesforce Commerce Cloud Store B2B vs B2C Templates	Commerce	Templates ( B2B, B2C )	
13	Headless Commerce Checkout	Checkout	Headless Commerce Checkout API ( Postman )	
14	Product Sets for B2B and DTC Commerce Cloud	Product	Product Set (번들), Product Class : Set, B2C ?	"Product Set : This product is a special type and is not used to add to the cart and purchase, just to group items together.
 - Product1 : This is one of the items that is bundled together but can also be bought separately. This product requires all the normal records - pricebook, entitlement, category, along with a relationship to the set.
 - Product2 :

Object
- New Product Set
- Category
- Commerce Entitlement Policies
- Child Products

Components
- Product Set ( Actual Price, Original Price, .... )"
15	D2C Guest Checkout with Salesforce Commerce Cloud	Checkout	Guest Checkout, Order	
16	Trilblazer DX - Going Headless with B2B Commerce	Checkout	Headless Commerce Checkout API ( node )	
17	Product Readiness	Product	Product Score	
18	Order Confimation Email with Marketing Cloud Pt1	Checkout	Marketing Cloud (Email)	
19	Order Confimation Email with Marketing Cloud Pt1	Checkout	Marketing Cloud (Email)	
20	How to translate content on commmerce cloud	Commerce	Translate (Global, Navigation, Experience, Product)	
21	Getting Started with B2B Commerce LWR	Front	LWR Started	
22	Setup Checkout in B2B Commerce LWR	Checkout	LWR Checkout, Order	
23	Styling your storefront with B2B Commerce LWR	Front	LWR (Theme, Component )	
24	Setup Promotions in Salesforce B2B & D2C Commerce	Promotions	Promotion, Coupon	
25	Salesforce Summer'23 Commerce Release	Relase	Extensions Services, Payments, Pay Now, Guest Checkout, Export Products, Wishlist	
26	Advanced Promotions in Salesforce B2B & D2C Commerce	Promotions	Tiers, Rank, Priority	
27	Expressions with Salesforce Commerce Cloud	Front	Expression ( 표현식 )	
28	Setup a buyer in B2B Commerce & D2C Commerce	User	Buyer, Account, User, Permission	
29	Quantity Rules in B2B & D2C Commerce	Checkout	수량규칙	
30	Code It Forward Launch	Checkout	Custom Component ( Cart Summary, Shipping Instructions, Shipping Methods )	
31	Salesforce Commerce Cloud Objects & Fields Pt1	Commerce	Object ( Store, Product, Buyer )	"Store
 - Store (WebStore) : Represents a commerce store.
 - Store Catalog (WebStoreCatalog) : Represents the collection of products associated with a store.
 - Registered External Service (RegisteredExternalService) : Represents a registered external service used for checkout integrations by data integrators.
 - Payment Gateway (PaymentGateway) : Platform object that represents the connection to an external payment gateway.
 - Payment Gateway Provider (PaymentGatewayProvider) : Setup entity for payment gateways. Defines the connection to a payment gateway Apex adapter.

Product
 - Product (Product2) : Represents a product that your company sells.
 - Pricebook (Pricebook2) : Respresents a price book that contains the list of products that your org sells.
 - Price Adjustment Schedule (PriceAdjustmentSchedule) : Respresents a series of tiered discounts based on the number of items purchased.
 - Category (ProductCategory) : Represents the category that products are organized in.
 - Entitlement Policy (CommerceEntitlementPolicy) : Represents an entilement policy, which determines what products and prices a user can see.
 - Product Variation (Product Attribute) : Represents the attributes that can be associated with a product.
 - Quantity Rule (PurchseQuantityRule) : Represents the rules that will be applied to the product in the storefront.
 - Product Medi (ProductMedia) : Represents the rich media, including images and attachments, that can be added to products.

Buyer
 - Account (Account) : Represents an individual account, which an organization or person involved with your business (such as customers, competitors, and partners).
 - Contact Point Address (ContactPointAddress) : Represents a contact's billing or shipping address, which is associated with an individual or person account.
 - Buyer Group (BuyerGroup) : Represents a member of a buyer group.
 - Buyer Account (BuyerAccount) : Represents an account that is enabled as a buyer for Lightning B2B Commerce.
 - Contact (Contact) : Represents a contact, which is a person associated with an account.
 - User (User) : Represents a user in your organization
"
32	Salesforce Commerce Cloud Objects & Fields Pt2	Commerce	Object ( Cart, Promotion, Order )	
33	Custom Purchase Order in Commerce Cloud LWR Checkout	Checkout	Purchase Order	
34	Dreamforce '23 Network with Commerce Trailblazers	Relase		
35	Salesforce B2B Commerce Winter 2 Relese	Relase	Checkout Component, Einstein, CSS, Larger Carts, Faster Add-to-cart, Easy Commerce Setup	
36	Salesforce Commerce Cloud Alternative Payments	Checkout	Payment Gateway	


-----------------------

, IsActive, CreatedDate, CreatedById, LastModifiedDate, LastModifiedById, SystemModstamp, LastViewedDate, LastReferencedDate
, CurrencyIsoCode, RecordTypeId

-- null
, Description, Family, ExternalDataSourceId, ExternalId, DisplayUrl, QuantityUnitOfMeasure, ConnectionReceivedId, ConnectionSentId
, StockKeepingUnit, B2BUseYN__c, ProductDivision__c, Client__c, Kondm__c, Giprice__c, Netpr__c, DOGUB__c
, ZDROP_DATE__c, Waerk__c, Df_gubun__c, Uncob__c, Bonus__c, Vmstb__c, Vtext__c, Vmsta__c, ZRTS_DATE__c
, Bwtar__c, Vmstd__c, Datab__c, Datbi__c, Mwsb__c, Taxm1__c, Taxm2__c, INPDATE__c, INPNAME__c, UPDDATE__c
, BoxSize__c, CMSActiveFlag__c, CREATE_DTTM__c, CREATOR_ID__c, CommercialCd__c, CustModelDesc__c, DelYN__c, Dimension__c
, Entry__c
, GSCMGeneration__c, GSCMInch__c, GSCMSales_YN_Dsctnu__c, GSCMYieldAfm__c, GSCMYieldInit__c
, GrossWeight__c, Hegubun__c, HevalidFrom__c, HevalidTo__c, HotelTVYN__c, ISExclusive__c, ITLoginYn__c, ImgPath__c
, Incrementing__c, Lvorm__c, MODEL_NM__c, MiniOrderQty__c, ModelStatus__c
, MultipleFlag__c, Netweight__c, NewGubunCD__c, NewYN__c
, OrderUseYN__c, PalletQty__c
, ProductDesc2__c, Product_Type__c, Project__c, SAPDelYN__c
, SegmentNm__c, SoftwareYN__c, StockQty__c, Unit__c, UpDate__c, UpdateDtTm__c, UpdaterId__c
, Voleh__c, Volum__c, Volume__c, WebUrl__c, WghtUnitCd__c, WrntyTypeCd__c, ZropDate__c, ZrtsDate__c
, VolumeUnitCd__c
, Knox_LV1__c, Knox_LV2__c, Knox_LV3__c, GSCMProjectSub__c, SolutionCompany__c, SolutionContact__c, SolutionMobile__c, SolutionName__c
, SolutionPhone__c, SolutionPosition__c, WarrantyPeriod__c
, DSS_gubun__c, Business_gubun__c

-- false
, IsDeleted, IsArchived, BluePrintYn__c, Dummy__c

--- 제품 조회
select Id, ExternalKeyTxt__c, ExternalKey__c, ProductCode, Name
, GSCMNM__c, GSCMProductGRPNewNM__c
, GSCMProductNM__c
, ModelGroup__c, ModelGrpCD__c
, WRKST__c
, ModelName__c, TOOLNAME__c
, GSCMAttb05__c, GSCMAttb06__c, GSCMAttb07__c

, ClassCategory__c
, Section__c
, Type__c

, Matkl__c, MATNR__c, MAKTX__c, Prodh__c, Zchannel__c, Versg__c, Dwerk__c
, Mtvfp__c, Spart__c, Mtpos__c, Mvgr1__c, Mvgr2__c, Mvgr3__c, Mvgr4__c, Mvgr5__c
, Ersda__c, Laeda__c, Groes__c, Ean11__c, Provg__c, Ktgrm__c
, Brgew__c
, GERPPlant__c
, GSCMBuyer__c, GSCMChangeYN__c, GSCMColorTypeCode__c, GSCMGbmCD__c

, GSCMProduction_YN_Dsctnu__c, GSCMProject__c
, Gewei__c
, Meins__c

, Mtart__c
, Ntgew__c, PRODUCT_TYPE_CD__c, PetNm__c

, SalesOrges__c
, ProductLine__c, MigRowId__c
, FOC__c
, GSCMAttb09__c, GSCMAttb12__c, GSCMAttb15__c

, fm_P1H__c, fm_P2H__c, fm_P3H__c, fm_P4H__c, fm_P5H__c
, GSCMProductGRPNM__c
, fm_GSCMProductDVGRPNewNM__c, fm_Prodh__c, fm_Prodh1114__c, fm_Product_Type_cd__c

, Division__c, SECORG_ID__c

 from Product2 
where SECORG_ID__c = 'SEI'
 and Section__c = 'MONITOR'
 and ModelGroup__c = 'SMART SIGNAGE'
order by ProductCode 

select Meins__c, count(id)
from Product2 
where SECORG_ID__c = 'SEI' 
group by Meins__c


select Section__c, count(id)
from Product2 
where SECORG_ID__c = 'SEI' 
group by Section__c

