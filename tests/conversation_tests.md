## Story from conversation with tester2 on March 26th 2020

* greet: hi
    - utter_greet
* transfer_money: i want to transfer money
    - transfer_form
    - form{"name":"transfer_form"}
    - slot{"requested_slot":"PERSON"}
* goodbye: [David](PERSON)
    - slot{"PERSON":"David"}
    - transfer_form
    - slot{"PERSON":"David"}
    - slot{"requested_slot":"amount-of-money"}
* inform: [600](amount-of-money)
    - slot{"amount-of-money":600}
    - transfer_form
    - slot{"amount-of-money":600}
    - slot{"requested_slot":"confirm"}
* affirm: yes please
    - transfer_form
