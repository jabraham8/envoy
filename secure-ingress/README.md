# Secure Reverse edge proxy

It is a clone of ingress but with JWT security enabled. 
Check ingress README for more info

## Test

curl -i secure-ingress-envoy.192.168.42.217.nip.io/petstore/petstore/1?includePets=false -H "Authorization: Bearer eyJhbGciOiJSUzI1NiIsImtpZCI6InRlc3QiLCJ0eXAiOiJKV1QifQ.eyJhdWQiOiJib29rcy5yZWFkIiwiZXhwIjoyMjIxMDM5NTUyLCJpc3MiOiJ0ZXN0Iiwic3ViIjoiYm9iIn0.4P53UPoFm4BsDSzWwu8u84Dv--kkdBlI1amxDYrcfsEs-PP3rZ80Vzx3b0cOLcSNoGwBSsYzfj9cCEd7KCOc87rRaeI16MEefMxIyDMPl395BoTo5g44r7pTMPG6Z8HC5T2abi5-LmlKrwri3FSRfy0BOJAtLDRF4ugy-sa5FAx9KWPu9hdd4CAXZc8gwPIGFC21qGVE6_GJtyF0KeGQG-Vldkd4M1PdhQGDvV0cqiWQlapqkLaGW98A_YJJr9qcMHidBfBdg6_ZciGjs8Rq71Jeh2X6OXeNG5eP6ofsJ0m9Uf0B8Wz65nknSMu3KrGm7iNca1A0IV17qVf-QSjD9w"
