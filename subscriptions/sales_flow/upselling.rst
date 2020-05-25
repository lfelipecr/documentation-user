=====================
Upsell a subscription
=====================

Subscriptions are recurrent and go on indefinitely. As time passes by, our customers may want to
modify them. We must then be able to adapt the prices or change the products’ quantities to
accommodate their needs. Two situations can happen:

1. **Loyal customers:** This kind of customers already trust you as a brand. Therefore, you are
   confident regarding what you offer since they keep paying for your products and services.
   Consequently, it is easier to sell them something additional than it would be to a
   new customer.

2. **New customers:** For this kind of customers, you have to come with something new, something
   attractive. What about discounts? Typically, every subscriptions end after a certain given time.
   Making these types of offers for new customers strengthens your relationships with them and also
   increases their retention.

.. raw:: html

   <div align="center" style="color:#AD5E99; font-size: 2rem ;margin: 20px 0"> <b>Upselling can make
   a subscription last longer.</b> </div>

Configuration
=============

As previously explained, to upsell a subscription to new customers, it is recommended to offer
*Discounts*. To activate this options, you have to go to
:menuselection:`Sales → Configuration → Settings` and under the *Pricing* category, you have the
possibility to grant discounts on sales order lines.

.. image:: media/upsell_1.png
  :align: center
  :alt: Activation of the discount option in Odoo Sales

Upsell your first subscription
==============================

Before upselling a subscription, be sure to check out our documentation on how to
:doc:`Create a quotation <../../subscriptions/sales_flow/create_a_quotation>` using subscription
products. Indeed, once confirmed, a quotation becomes a sales order and a new subscription is
automatically created. Therefore, this subscription has the status *In progress*. From there, you
have the possibility to upsell your subscription.

.. image:: media/upsell_2.png
  :align: center
  :alt: Upsell your subscription with Odoo Subscriptions

By using the smart button *Upsell*, you will be able to create a new quotation with new subscription
products and send it to your customers for approval.

.. image:: media/upsell_3.png
  :align: center
  :alt: Add products to your subscription via the upsell option in Odoo Subscriptions

.. important::
   When the quotation is confirmed by your customers, the products will be added to the initial
   subscription. Quotation prices will be prorated to the remaining time of the current invoicing
   period.

Of course, before sending this new quotation to your customers, you can change the unit price, taxes
and even the discount you want to offer. The smart button *Customer preview* is useful for mimicking
the customer's reaction. For this case, we can confidently say that the customer will *Sign and pay*
this new quotation. When it is done, you have to go back in edit mode, confirm the quotation and
click on the smart button *Subscriptions* to visualize all updates.

.. image:: media/upsell_4.png
  :align: center
  :alt: Visualize all your subscriptions updates with Odoo Subscriptions

From there, you can see that an additional line is added to the subscription with the extra service
the customer would like to purchase. In addition, a second sales order will be created.

.. image:: media/upsell_5.png
  :align: center
  :alt: Visualize all your subscriptions updates with Odoo Subscriptions

.. seealso::
  - :doc:`../../subscriptions/sales_flow/create_a_quotation`