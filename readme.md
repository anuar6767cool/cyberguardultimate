#cyber-guard-ultimate
Clear-Host

Write-Host "================================"
Write-Host "     CYBER GUARD ULTIMATE 2026"
Write-Host "================================"
Write-Host ""
Write-Host "1 - Проверить состояние защиты"
Write-Host "2 - Запустить быструю проверку"
Write-Host "3 - Обновить базы Defender"
Write-Host "0 - Выход"
Write-Host ""

$choice = Read-Host "Выбери действие"

switch ($choice) {
    "1" {
        Get-MpComputerStatus |
        Select-Object AntivirusEnabled,
        RealTimeProtectionEnabled,
        AntivirusSignatureLastUpdated |
        Format-List
    }
    "2" {
        Start-MpScan -ScanType QuickScan
        Write-Host "Проверка запущена."
    }
    "3" {
        Update-MpSignature
        Write-Host "Запрос обновления выполнен."
    }
    "0" {
        exit
    }
    default {
        Write-Host "Неизвестная команда."
    }
}

Read-Host "Нажми Enter для выхода"Clear-Host

Write-Host "================================"
Write-Host "     CYBER GUARD ULTIMATE 2026"
Write-Host "================================"
Write-Host ""
Write-Host "1 - Проверить состояние защиты"
Write-Host "2 - Запустить быструю проверку"
Write-Host "3 - Обновить базы Defender"
Write-Host "0 - Выход"
Write-Host ""

$choice = Read-Host "Выбери действие"

switch ($choice) {
    "1" {
        Get-MpComputerStatus |
        Select-Object AntivirusEnabled,
        RealTimeProtectionEnabled,
        AntivirusSignatureLastUpdated |
        Format-List
    }
    "2" {
        Start-MpScan -ScanType QuickScan
        Write-Host "Проверка запущена."
    }
    "3" {
        Update-MpSignature
        Write-Host "Запрос обновления выполнен."
    }
    "0" {
        exit
    }
    default {
        Write-Host "Неизвестная команда."
    }
}

Read-Host "Нажми Enter для выхода"Clear-Host

Write-Host "================================"
Write-Host "     CYBER GUARD ULTIMATE 2026"
Write-Host "================================"
Write-Host ""
Write-Host "1 - Проверить состояние защиты"
Write-Host "2 - Запустить быструю проверку"
Write-Host "3 - Обновить базы Defender"
Write-Host "0 - Выход"
Write-Host ""

$choice = Read-Host "Выбери действие"

switch ($choice) {
    "1" {
        Get-MpComputerStatus |
        Select-Object AntivirusEnabled,
        RealTimeProtectionEnabled,
        AntivirusSignatureLastUpdated |
        Format-List
    }
    "2" {
        Start-MpScan -ScanType QuickScan
        Write-Host "Проверка запущена."
    }
    "3" {
        Update-MpSignature
        Write-Host "Запрос обновления выполнен."
    }
    "0" {
        exit
    }
    default {
        Write-Host "Неизвестная команда."
    }
}

Read-Host "Нажми Enter для выхода"
