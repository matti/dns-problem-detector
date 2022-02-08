# dns-problem-detector

queries a nameserver continously and stops if the answer does not contain the expected string

example: query 1.1.1.1 a record for www.microsoft.com and assert that "akamaiedge" is found

    ./dns-problem-detector 1.1.1.1 a www.microsoft.com akamaiedge