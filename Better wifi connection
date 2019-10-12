cd\
@echo off
color 0a
title get better internet
echo get better internet



ipconfig
ipconfig /flushdns
ipconfig /registerdns
ipconfig /release
ipconfig /renew
netsh int ip reset
netsh winsock reset
netsh int tcp show global
netsh int tcp set global autotuninglevel=normal
netsh int tcp set heuristics disabled
netsh int tcp set chimney=enabled
netsh int tcp set congestionprovider=ctcp 
shutdown /r
