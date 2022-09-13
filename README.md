# try_API_IP
Practice of javascript with REGEX

try it here:
https://iridescent-boba-47f5e9.netlify.app

codi.link for the code:
https://codi.link/PCFET0NUWVBFIGh0bWw+DQo8aHRtbCBsYW5nPSJlcyI+DQoNCjxoZWFkPg0KICA8bWV0YSBjaGFyc2V0PSJVVEYtOCI+DQogIDxtZXRhIGh0dHAtZXF1aXY9IlgtVUEtQ29tcGF0aWJsZSIgY29udGVudD0iSUU9ZWRnZSI+DQogIDxtZXRhIG5hbWU9InZpZXdwb3J0IiBjb250ZW50PSJ3aWR0aD1kZXZpY2Utd2lkdGgsIGluaXRpYWwtc2NhbGU9MS4wIj4NCiAgPHRpdGxlPlBydWViYUFQSTwvdGl0bGU+DQo8L2hlYWQ+DQoNCjxib2R5Pg0KICA8bGluayByZWw9InN0eWxlc2hlZXQiIGhyZWY9Imh0dHBzOi8vdW5wa2cuY29tL0BwaWNvY3NzL3BpY29AbGF0ZXN0L2Nzcy9waWNvLm1pbi5jc3MiPg0KICA8bWFpbiBjbGFzcz0iY29udGFpbmVyIj4NCiAgICA8Zm9ybSBpZD0iZm9ybSI+DQogICAgICA8bGFiZWw+DQogICAgICAgIElQIGluZm9ybWFudGUNCiAgICAgICAgPGlucHV0IHJlcXVpcmVkIGlkPSJpbnB1dCIgdHlwZT0idGV4dCIgcGxhY2Vob2xkZXI9IkludHJvZHVjZSBhcXXDrSBsYSBJUCI+DQogICAgICAgIDxzbWFsbD5EZWJlIHNlciBkZSBlc3RhIGZvcm1hOiA1NC44NS4xMzIuMjA1PC9zbWFsbD4NCiAgICAgIDwvbGFiZWw+DQogICAgICA8YnV0dG9uIHR5cGU9InN1Ym1pdCIgaWQ9InN1Ym1pdCI+QnVzY2FyIGluZm8gZGUgZXN0YSBJUDwvYnV0dG9uPg0KICAgIDwvZm9ybT4NCg0KICAgIDxkaXY+DQogICAgICA8cHJlIGlkPSJyZXN1bHRzIj4NCg0KICAgICAgPC9wcmU+DQogICAgPC9kaXY+DQogIDwvbWFpbj4NCjwvYm9keT4NCg0KPC9odG1sPg==%7C%7CLy9AdHMtY2hlY2sNCi8vIE5lZWQgdG8gdGFrZSB0aGUgT1BUSU9OUyBmcm9tIHJhcGlkQVBJIElQIEdlb2xvY2F0aW9uIGFuZCBUaHJlYXQgRGV0ZWN0aW9uDQovLyBodHRwczovL3JhcGlkYXBpLmNvbS9pcGZpbmQvYXBpL2ZpbmQtYW55LWlwLWFkZHJlc3Mtb3ItZG9tYWluLWxvY2F0aW9uLXdvcmxkLXdpZGUNCg0KY29uc3QgeW91ckFwaUtleSA9ICJ5b3VyIGtleSIgLyogVW5kZXIgSVAgaW4gcmVxdWlyZWQgcGFyYW1ldGVycywgaW4gcmFwaWQgQVBJICovDQoNCmNvbnN0IE9QVElPTlMgPSB7DQogIC8vWW91ciBrZXlzIGhlcmUNCn07DQoNCmNvbnN0IGZldGNoSVBpbmZvID0gaXAgPT4gew0KICByZXR1cm4gZmV0Y2goYGh0dHBzOi8vZmluZC1hbnktaXAtYWRkcmVzcy1vci1kb21haW4tbG9jYXRpb24td29ybGQtd2lkZS5wLnJhcGlkYXBpLmNvbS9pcGxvY2F0aW9uP2lwPSR7aXB9JmFwaWtleT0ke3lvdXJBcGlLZXl9YCwgT1BUSU9OUykNCiAgICAudGhlbihyZXMgPT4gcmVzLmpzb24oKSkNCiAgICAuY2F0Y2goZXJyID0+IGNvbnNvbGUuZXJyb3IoZXJyKSkNCn0NCg0KY29uc3QgJCA9IHNlbGVjdG9yID0+IGRvY3VtZW50LnF1ZXJ5U2VsZWN0b3Ioc2VsZWN0b3IpOw0KDQpjb25zdCAkZm9ybSA9ICQoJyNmb3JtJyk7DQpjb25zdCAkaW5wdXQgPSAkKCcjaW5wdXQnKTsNCmNvbnN0ICRzdWJtaXQgPSAkKCcjc3VibWl0Jyk7DQpjb25zdCAkcmVzdWx0cyA9ICQoJyNyZXN1bHRzJyk7DQoNCmZ1bmN0aW9uIGNoZWNrU3RyaW5nKHN0cmluZykgew0KICBsZXQgcmVndHJ5ID0gL14oKDI1WzAtNV18KDJbMC00XXwxXGR8WzEtOV18KVxkKShcLig/ISQpfCQpKXs0fSQvOw0KICByZXR1cm4gcmVndHJ5LmV4ZWMoc3RyaW5nKTsNCn0NCg0KJGZvcm0uYWRkRXZlbnRMaXN0ZW5lcignc3VibWl0JywgYXN5bmMgKGV2ZW50KSA9PiB7DQogIGV2ZW50LnByZXZlbnREZWZhdWx0KCkNCiAgY29uc3QgeyB2YWx1ZSB9ID0gJGlucHV0DQogIGlmICghdmFsdWUpIHJldHVybg0KDQogIGlmICghY2hlY2tTdHJpbmcodmFsdWUpKSB7DQogICAgJGlucHV0LnNldEF0dHJpYnV0ZSgnYXJpYS1pbnZhbGlkJywgJ3RydWUnKQ0KICAgIHNldFRpbWVvdXQoKCkgPT4gew0KICAgICAgJGlucHV0LnJlbW92ZUF0dHJpYnV0ZSgnYXJpYS1pbnZhbGlkJykNCiAgICB9LCAxMDAwKQ0KICAgIHJldHVybg0KICB9IGVsc2Ugew0KICAgICRpbnB1dC5zZXRBdHRyaWJ1dGUoJ2FyaWEtaW52YWxpZCcsICdmYWxzZScpDQogICAgc2V0VGltZW91dCgoKSA9PiB7DQogICAgICAkaW5wdXQucmVtb3ZlQXR0cmlidXRlKCdhcmlhLWludmFsaWQnKQ0KICAgIH0sIDEwMDApDQogIH0NCg0KDQoNCiAgJHN1Ym1pdC5zZXRBdHRyaWJ1dGUoJ2Rpc2FibGVkJywgJycpDQogICRzdWJtaXQuc2V0QXR0cmlidXRlKCdhcmlhLWJ1c3knLCAndHJ1ZScpDQoNCiAgY29uc3QgaXBJTkZPID0gYXdhaXQgZmV0Y2hJUGluZm8odmFsdWUpDQoNCiAgaWYoaXBJTkZPKSB7DQogICAgJHJlc3VsdHMuaW5uZXJIVE1MID0gSlNPTi5zdHJpbmdpZnkoaXBJTkZPLG51bGwsMik7DQogIH0NCg0KICAkc3VibWl0LnJlbW92ZUF0dHJpYnV0ZSgnZGlzYWJsZWQnKQ0KICAkc3VibWl0LnJlbW92ZUF0dHJpYnV0ZSgnYXJpYS1idXN5JykNCn0pDQo=
