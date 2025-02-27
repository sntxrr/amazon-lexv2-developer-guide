# SlotValueRegexFilter<a name="API_SlotValueRegexFilter"></a>

Provides a regular expression used to validate the value of a slot\.

## Contents<a name="API_SlotValueRegexFilter_Contents"></a>

 **pattern**   <a name="lexv2-Type-SlotValueRegexFilter-pattern"></a>
A regular expression used to validate the value of a slot\.  
 Use a standard regular expression\. Amazon Lex supports the following characters in the regular expression:   
+ A\-Z, a\-z
+ 0\-9
+ Unicode characters \("\\ u<Unicode>"\)
 Represent Unicode characters with four digits, for example "\\u0041" or "\\u005A"\.   
 The following regular expression operators are not supported:   
+ Infinite repeaters: \*, \+, or \{x,\} with no upper bound\.
+ Wild card \(\.\)
Type: String  
Length Constraints: Minimum length of 1\. Maximum length of 100\.  
Required: Yes

## See Also<a name="API_SlotValueRegexFilter_SeeAlso"></a>

For more information about using this API in one of the language\-specific AWS SDKs, see the following:
+  [ AWS SDK for C\+\+](https://docs.aws.amazon.com/goto/SdkForCpp/models.lex.v2-2020-08-07/SlotValueRegexFilter) 
+  [ AWS SDK for Go](https://docs.aws.amazon.com/goto/SdkForGoV1/models.lex.v2-2020-08-07/SlotValueRegexFilter) 
+  [ AWS SDK for Java V2](https://docs.aws.amazon.com/goto/SdkForJavaV2/models.lex.v2-2020-08-07/SlotValueRegexFilter) 
+  [ AWS SDK for Ruby V3](https://docs.aws.amazon.com/goto/SdkForRubyV3/models.lex.v2-2020-08-07/SlotValueRegexFilter) 