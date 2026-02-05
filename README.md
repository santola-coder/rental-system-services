



```RentalManagement.Application/
├── DTOs/
│   ├── Auth/
│   │   └── LoginDto.cs
│   │
│   ├── Tenant/
│   │   ├── CreateTenantDto.cs
│   │   └── TenantResponseDto.cs
│   │
│   ├── Lease/
│   │   └── CreateLeaseDto.cs
│   │
│   └── Payment/
│       └── CreatePaymentDto.cs
│
├── Interfaces/
│   └── Services/
│       ├── IAuthService.cs
│       ├── ITenantService.cs
│       ├── ILeaseService.cs
│       └── IPaymentService.cs
│
├── Services/
│   ├── AuthService.cs
│   ├── TenantService.cs
│   ├── LeaseService.cs
│   └── PaymentService.cs
│
├── Validators/
│   ├── LoginValidator.cs
│   └── CreateTenantValidator.cs
│
├── Exceptions/
│   ├── BusinessRuleException.cs
│   └── NotFoundException.cs
│
└── Common/
    └── JwtHelper.cs
