@RequestMapping(value = "/hello", method = RequestMethod.GET)
@ResponseBody

@ResponseBody
----------------
Annotation that indicates a method return value should be bound to the web response body.
Supported for annotated handler methods in Servlet environments.
As of version 4.0 this annotation can also be added on the type level in which case it is inherited and
does not need to be added on the method level.

shivani
