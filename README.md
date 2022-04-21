# ExchangeVersion
    This script will get the cumulative update version for the specified exchange server (2013/2016/2019).
 
    BuildNumbers link:
    https://docs.microsoft.com/en-us/exchange/new-features/build-numbers-and-release-dates?view=exchserver-2019
 
    Get-ExchangeServer | Get-ExchangeVersion
        Or
    Get-ExchangeVersion -ComputerName ExchSrv01, ExchSrv02
