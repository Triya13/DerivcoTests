Hi there, please follow the insctructions on how to run the tests and the answers to objective 4 :) 

Instructions to run:
1. Ensure you have Visual Studio(pref 2022) 
2. Install restSharp: Install-Package RestSharp (or Nuget manager interface)
3. Install NewtonSoft: Newtonsoft.Json (Nuget package)
4. Run test cases via Test Explorer in Visual Studio 

Objective 4:
Non-functional test 1: Performance test
- Analyse the response times and stability under loads of different sizes; max load will determine the stability
- Tool that would be used: Apache JMeter can be used to simulate multiple users and requests to measure the performance of the API.

Non-functional Test 2: Security/Penetration testing 
- vulnerabilities in the API, such as SQL injection, XSS (Cross-Site Scripting)
- try to mitigate vulnerabilities
- Tool that would be used: OWASP ZAP (Zed Attack Proxy) is a widely used security testing tool that can help in identifying security vulnerabilities in web applications and APIs
