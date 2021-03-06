# SquareConnect::Card

### Description

Represents the non-confidential details of a credit card.

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **String** | The card&#39;s unique ID, if any. | [optional] 
**card_brand** | **String** | The card&#39;s brand (such as &#x60;VISA&#x60;). See [CardBrand](#type-cardbrand) for all possible values. | [optional] 
**last_4** | **String** | The last 4 digits of the card&#39;s number. | [optional] 
**exp_month** | **Integer** | The month of the card&#39;s expiration date. This value is always between &#x60;1&#x60; and &#x60;12&#x60;, inclusive. | [optional] 
**exp_year** | **Integer** | The four-digit year of the card&#39;s expiration date. | [optional] 
**cardholder_name** | **String** | The cardholder name. This value is present only if this object represents a customer&#39;s card on file. | [optional] 
**billing_address** | [**Address**](Address.md) | The card&#39;s billing address. This value is present only if this object represents a customer&#39;s card on file. | [optional] 
**fingerprint** | **String** | The unique string fingerprint for the card. The fingerprint is based on the credit card number and is unique to the merchant. If a card is used at multiple locations for the same merchant, it will have the same fingerprint in each case. Note: Fingerprint may not exist on old transactions. | [optional] 


