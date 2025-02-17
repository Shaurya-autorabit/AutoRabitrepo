<?xml version="1.0" encoding="UTF-8"?>
<CustomMetadata xmlns="http://soap.sforce.com/2006/04/metadata" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <label>Default Top K For AutoComplete</label>
    <protected>false</protected>
    <values>
        <field>avnio__Description__c</field>
        <value xsi:type="xsd:string">Top-K sampling means sorting by probability and zero-ing out the probabilities for anything below the k&apos;th token. A lower value improves quality by removing the tail and making it less likely to go off topic. Can set the value from 10 to max_length</value>
    </values>
    <values>
        <field>avnio__Value__c</field>
        <value xsi:nil="true"/>
    </values>
</CustomMetadata>
