@echo off
:: Restart computer and enter firmware settings

:: Warning: This will force an immediate restart. Save any unsaved work before running.

set /p confirm=Are you sure you want to restart and enter firmware settings? (y/n): 

if /i "%confirm%"=="y" (
    shutdown /r /fw /f /t 0
) else (
    echo Restart cancelled.
    pause
)
