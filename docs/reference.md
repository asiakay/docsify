# [How-to: Command line arguments - bash](https://ss64.com/osx/syntax-args.html)
# [echo](https://ss64.com/osx/echo.html) - Display message on screen.

##    - [How Command Line Parameters Are Parsed](https://web.archive.org/web/20200402073506/http://daviddeley.com/autohotkey/parameters/parameters.htm)
##    - [How-to: macOS Environment variables](https://ss64.com/osx/syntax-env_vars.html)
##    - [How-to: Shell variables and Environment variables](https://ss64.com/osx/syntax-variables.html)





# Q. What is User Datagram Protocol (UDP)?
    - connects to wider ecosystem of option when programming using Real Time Communication(RTC)  
    - A Faster Alternative to Transmission Control Protocol (TCP) for sending and recieving data.

Source: [What is UDP](https://searchnetworking.techtarget.com/definition/UDP-User-Datagram-Protocol) (User Datagram Protocol)

    - a communications protocol primarily used for 
        - speeding up transmissions                                   
            - enabling the transfer of data 
                - before an agreement is provided by the receiving party.
        - establishing 
            - low-latency connections 
            - loss-tolerating connections 
                - between applications on the internet. 

        - UDP is beneficial in time-sensitive communications
            - voice over Internet Protocol (VoIP)
            - domain name system (DNS) lookup
            - video or audio playback

        - UDP alternative to Transmission Control Protocol (TCP)
            - similarities 
                - Both UDP and TCP run on top of IP** 
                - Are sometimes referred to as UDP/IP or TCP/IP
            - differences 
                - TCP supports host-to-host communication
                - TCP sends individual packets 
                - TCP considered a reliable transport medium. 
                - UDP enables process-to-process communication
                - UDP sends messages, called datagrams, 
                    - considered a best-effort mode of communications 
                    - the service does not provide any guarantees that
                        - data will be delivered 
                        - offer special features to retransmit 
                            - lost or 
                            - corrupted messages.
                - *** Does this mean no 404 notifications? ***

#### [Internet Protocol(IP)](https://searchunifiedcommunications.techtarget.com/definition/Internet-Protocol) is the method or protocol by which data is sent from one computer(host/client) to another on the internet. 

#### [Transmission Control Protocol (TCP)](https://searchnetworking.techtarget.com/definition/TCP) TCP is a connection-oriented protocol, which means a connection is established and maintained until the application programs at each end have finished exchanging messages. It determines how to break application data into packets that networks can deliver, sends packets to and accepts packets from the network layer, manages flow control and -- because it is meant to provide error-free data transmission -- handles retransmission of dropped or garbled packets and acknowledges all packets that arrive. In the Open Systems Interconnection (OSI) communication model, TCP covers parts of Layer 4, the transport layer, and parts of Layer 5, the session layer.

#### [TCP and UDP Socket API](https://www.w3.org/TR/tcp-udp-sockets/) This API provides interfaces to raw UDP sockets, TCP Client sockets and TCP Server sockets. As such, this requires a high level of trust in applications that use this API, since raw sockets can be used to work around the same origin security policy.



## [env](https://ss64.com/osx/env.html)
    - [List or Set environment variables]
    - [Optionally run a utility]

## [set](https://ss64.com/osx/set.html)
    - Change the value of a shell option 
    - Set the positional parameters, 
        - or display the names of shell variables 
        - and display the values of shell variables.



## [say](https://ss64.com/osx/say.html)
    - Convert text to audible speech.
        - This tool uses the Speech Synthesis manager 
            - to convert input text to audible speech and 
            - to play it play through the sound output device 
                - chose output devise in System Preferences 
                - or save converted text to speech file as an AIFF file.













