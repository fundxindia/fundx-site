<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>FundX – Smart Finance Platform</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      margin: 0;
      background: #ffffff;
      color: #111827;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
    }
    .card {
      max-width: 640px;
      padding: 32px 24px;
      box-shadow: 0 12px 30px rgba(15, 23, 42, 0.16);
      border-radius: 18px;
      text-align: center;
    }
    .logo {
      font-size: 32px;
      font-weight: 800;
      color: #F1B632;
      letter-spacing: 0.02em;
    }
    .tag {
      font-size: 15px;
      color: #4b5563;
      margin-top: 4px;
      margin-bottom: 16px;
    }
    .badge {
      display: inline-block;
      padding: 4px 10px;
      border-radius: 999px;
      font-size: 11px;
      background: #fef3c7;
      color: #92400e;
      font-weight: 600;
      margin-bottom: 12px;
    }
    h2 {
      font-size: 18px;
      margin-top: 8px;
      margin-bottom: 8px;
    }
    p {
      font-size: 13px;
      line-height: 1.5;
      color: #4b5563;
      margin: 4px 0;
    }
    .section-title {
      font-size: 14px;
      font-weight: 600;
      margin-top: 16px;
      margin-bottom: 4px;
    }
    .contact {
      margin-top: 16px;
      font-size: 12px;
      color: #6b7280;
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="logo">FundX</div>
    <div class="tag">Smart Finance Platform</div>

    <span class="badge">Internal prototype / testing only</span>

    <h2>What is FundX?</h2>
    <p>
      FundX is a personal technology prototype owned and operated by 《☆》.
      It is used for internal testing, education and product experiments.
    </p>
    <p>
      This app simulates wallet balances, loan offers and repayments using a secure
      Supabase backend. It is <strong>not</strong> a bank, NBFC or regulated financial
      institution.
    </p>

    <div class="section-title">Important disclaimer</div>
    <p>
      All “wallet balance”, “loans”, “interest”, “limits” and similar values shown
      inside the FundX mobile apps are simulated records for product design only.
      They do <strong>not</strong> represent real money or legally enforceable obligations.
    </p>

    <div class="section-title">Usage</div>
    <p>
      • Used only by the owner and a small internal test group.<br/>
      • Data is stored securely on Supabase (PostgreSQL).<br/>
      • No production customers or public onboarding is enabled.
    </p>

    <div class="section-title">Contact</div>
    <p class="contact">
      For questions about this prototype, write to:
      <br/><strong>fundxindia@gmail.com</strong>
    </p>
  </div>
</body>
</html>
