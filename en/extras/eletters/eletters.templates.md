---
title: "Templates"
_old_id: "833"
_old_uri: "revo/eletters/eletters.templates"
---

## Making a custom Template

- The easiest way is to just Duplicate the EletterSample Template. Go to the Elements tab on the left panel in your MODX Manager. Expand Templates then expand Eletters. Once you see EletterSample, right click on it. A dialog will pop up and then just click on Duplicate Template. Then fill in the name you want.
  ![](/download/attachments/39355138/duplicate.png?version=1&modificationDate=1335818884000)
- Now review the code and then make your own code. Note you need to have all of the Eletter TVs selected otherwise the program will not generate an email.

## Placeholders you can use in the Template

All MODX tags and elements as you would in a normal template are available. These placeholders are also available within any TV or the content area.

Example usage: \[\[+manageSubscriptionsUrl\]\]

| Name                                                        | Description                                                                                                                                                                               |
| ----------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| trackingImage                                               | Use \[\[+trackingImage\]\] for an image, you can also put a custom image/banner doing this: \[\[+trackingImage\]\]image=test.jpg then put the image in assets/components/eletters/images/ |
| Example useage: <img src="\[\[+trackingImage\]\]" alt="" /> |
| manageSubscriptionsUrl                                      | The URL that allows the subscriber to manager their subscriptions, the generated links has unique subscriber code                                                                         |
| unsubscribeUrl                                              | The URL that allows the subscriber to unsubscribe from your eletters, the generated links has unique subscriber code                                                                      |
| manageSubscriptionsID                                       | The page ID of the manage subscriptions page                                                                                                                                              |
| unsubscribeID                                               | The page ID of the unsubscribe page                                                                                                                                                       |

### Subscriber Personal Information Placeholders

Note you need to have actually collected each specific field if you wish to use them. It is recommended that you set first\_name, last\_name and email to required on your signup forms and set the other fields as you wish. date\_created is auto generated so don't put that field on your signup form.

| Name          | Description                                                            |
| ------------- | ---------------------------------------------------------------------- |
| first\_name   | First name                                                             |
| m\_name       | Middle name                                                            |
| last\_name    | Last name                                                              |
| fullname      | First name + Last name                                                 |
| company       | Company                                                                |
| address       | Street Address                                                         |
| city          | City                                                                   |
| state         | State                                                                  |
| zip           | Zip or Postal Code                                                     |
| country       | Country                                                                |
| email         | Email address                                                          |
| phone         | Phone number                                                           |
| cell          | Cellphone number                                                       |
| crm\_id       | CRM (Customer Relationship Manager) ID, if you use a product like this |
| date\_created | The date the person subscribed or when an admin added their account    |

## See Also

1. [Eletters.API](extras/eletters/eletters.api)
2. [Eletters.FormIt](extras/eletters/eletters.formit)
3. [Eletters.Import CSV](extras/eletters/eletters.import-csv)
4. [Eletters.Templates](extras/eletters/eletters.templates)
