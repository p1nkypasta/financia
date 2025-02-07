<script>
    let questions = [
      {
        question: "Which of the following equations cannot be derived from the basic accounting equation:",
        options: [
          "Assets – Liabilities = Owner’s Equity",
          "Liabilities = Assets – Owner’s Equity",
          "Owner’s Equity – Liabilities – Assets",
          "Assets – Owner’s Equity = Liabilities"
        ],
        correctAnswer: "Owner’s Equity – Liabilities – Assets",
        selectedOption: "",
        feedback: ""
      },
      {
        question: "Magic Forest Land Development Corporation sold a portion of land at a profit. This will cause:",
        options: [
          "A decrease in assets and liabilities",
          "An increase in assets and liabilities",
          "An increase in assets and owner’s equity",
          "A decrease in assets and owner’s equity"
        ],
        correctAnswer: "An increase in assets and owner’s equity",
        selectedOption: "",
        feedback: ""
      },
      {
        question: "Arrowhead Lake Boat Shop bought a $700 electric hoist (equipment) to lift engines out of boats. The boat shop paid $200 in cash and promised to pay the balance in 20 days. This transaction will cause:",
        options: [
          "The boat shop’s assets to increase by $700 and liabilities to increase by $500",
          "Assets to increase by $500 and owner’s equity to decrease",
          "No change in total assets, but a $500 increase in liabilities and a similar decrease in owner’s equity",
          "No change in owner’s equity, but a $500 increase in both assets and liabilities"
        ],
        correctAnswer: "No change in owner’s equity, but a $500 increase in both assets and liabilities",
        selectedOption: "",
        feedback: ""
      },
      {
        question: "Which of the following errors would NOT be disclosed by the Trial Balance:",
        options: [
          "The collection of a $520 accounts receivable was entered in T-accounts as a debit of $520 to Cash and a credit of $502 to Accounts Receivable",
          "The collection of $200 accounts receivable was entered as a $200 debit to Cash and a $200 debit to Accounts Receivable",
          "The collection of a $1,000 accounts receivable was entered in T-accounts as a debit to Land and a credit to Cash",
          "None of the above"
        ],
        correctAnswer: "The collection of a $1,000 accounts receivable was entered in T-accounts as a debit to Land and a credit to Cash",
        selectedOption: "",
        feedback: ""
      },
      {
  question: "If the assets of a company are $10,000 and the liabilities are $7,000, then the correct figure for Owner’s Equity is:",
  options: [
    "$17,000",
    "$10,000",
    "$3,000",
    "$5,000"
  ],
  correctAnswer: "$3,000",
  selectedOption: "",
  feedback: ""
},
{
  question: "A business borrows $10,000 from the bank. The entry to record the transaction is:",
  options: [
    "Debit Cash and Credit Capital",
    "Debit Cash and Credit Bank Loan",
    "Debit Bank Loan and Credit Capital",
    "Debit Bank Loan and Credit Cash"
  ],
  correctAnswer: "Debit Cash and Credit Bank Loan",
  selectedOption: "",
  feedback: ""
},
{
  question: "A business buys land for $50,000 on credit. In recording the transaction, the effect on the accounting equation will be:",
  options: [
    "Assets both increase and decrease",
    "Assets increase and liabilities increase",
    "Assets increase and liabilities decrease",
    "Assets increase and capital increases"
  ],
  correctAnswer: "Assets increase and liabilities increase",
  selectedOption: "",
  feedback: ""
},
{
  question: "If an entry involves a debit to an asset account, it may also involve a credit to:",
  options: [
    "A liability account",
    "An asset account",
    "A capital account",
    "All of the above"
  ],
  correctAnswer: "All of the above",
  selectedOption: "",
  feedback: ""
},
{
  question: "If the owner of a business pays cash to repair the company’s delivery truck:",
  options: [
    "Cash is debited and delivery truck is credited",
    "Delivery truck is debited and cash is credited",
    "An expense account is debited and cash is credited",
    "The capital account is credited and delivery truck is credited"
  ],
  correctAnswer: "An expense account is debited and cash is credited",
  selectedOption: "",
  feedback: ""
},
{
  question: "A debit to an account may:",
  options: [
    "Increase any asset",
    "Decrease any asset",
    "Increase any liability",
    "Increase capital"
  ],
  correctAnswer: "Increase any asset",
  selectedOption: "",
  feedback: ""
},
{
  question: "In reviewing the books for his company, the owner noted that one transaction was recorded as a $500 debit to Cash and a $500 debit to Furniture & Fixtures. The result of this error will cause:",
  options: [
    "The cash to be overstated by $500",
    "The trial balance to be understated by $500",
    "The furniture & fixtures account to be overstated by $500",
    "The cash account to be overstated by $1,000"
  ],
  correctAnswer: "The cash account to be overstated by $1,000",
  selectedOption: "",
  feedback: ""
},
{
  question: "Which account would appear on the Trial Balance, Income Statement, and Balance Sheet?",
  options: [
    "Revenue",
    "Cash",
    "Drawings",
    "None of the Above"
  ],
  correctAnswer: "None of the Above",
  selectedOption: "",
  feedback: ""
},
{
  question: "Another name for the balance sheet is:",
  options: [
    "Statement of financial position",
    "Statement of financial performance",
    "Statement of financial profit",
    "Statement of financial gains"
  ],
  correctAnswer: "Statement of financial position",
  selectedOption: "",
  feedback: ""
},
{
      question: "What is the goal of the last step of the Accounting Cycle?",
      options: [
        "Add Journal entries to the ledger",
        "Complete adjustments",
        "Close the temporary accounts",
        "None of the above"
      ],
      correctAnswer: "Close the temporary accounts",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "The term ‘debit’ in Accounting means:",
      options: [
        "Right",
        "Left",
        "Increase",
        "Decrease"
      ],
      correctAnswer: "Left",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "The account that helps recognize the expenses that helped generate revenue during the period that it is earned is known as the:",
      options: [
        "Revenue Recognition GAAP",
        "Matching Principle",
        "Historical Cost Concept",
        "The Business Entity Concept"
      ],
      correctAnswer: "Matching Principle",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "The owner feels that a receipt for an asset purchase that states $100 should be valued at $200. This is not allowed according to the:",
      options: [
        "Matching Principle",
        "Revenue Recognition GAAP",
        "Historical Cost Concept",
        "None of the above"
      ],
      correctAnswer: "Historical Cost Concept",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "The official financial statements are:",
      options: [
        "Trial Balance, Balance Sheet, and Cash Flow Statement",
        "Trial Balance, Income Statement, Cash Flow Statement",
        "Income Statement, Balance Sheet, Cash Flow Statement",
        "Trial Balance, Balance Sheet, Income Statement"
      ],
      correctAnswer: "Income Statement, Balance Sheet, Cash Flow Statement",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "The following are end users of financial statements:",
      options: [
        "Customers, shareholders, Owners",
        "Shareholders, Owners, Managers",
        "Managers, Customers, Investors",
        "Customers, Managers, Shareholders"
      ],
      correctAnswer: "Shareholders, Owners, Managers",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "What is a contra account?",
      options: [
        "An account that is complementary to another account",
        "An account that represents the net total of two accounts",
        "An account that only appears on the balance sheet",
        "An account that is married to another account to produce a net total"
      ],
      correctAnswer: "An account that is married to another account to produce a net total",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "If Total Revenue is $14,000, Net Sales are $10,000, and COGS is $6,000, what is Gross Profit?",
      options: [
        "$6,000",
        "$10,000",
        "$4,000",
        "It can’t be determined"
      ],
      correctAnswer: "$4,000",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "From 2022 to 2023, Net Sales increased $1,000, and Cost of Goods Sold decreased $4,000. This company’s Gross Profit Margin:",
      options: [
        "Increased",
        "Decreased",
        "Remained the same",
        "It cannot be determined"
      ],
      correctAnswer: "Increased",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "If Gross Profit was $20,000, and Cost of Goods Sold was $12,000, what is Net Income?",
      options: [
        "$8,000",
        "$12,000",
        "It is a Net Loss, not Net Income",
        "Net Income cannot be determined - cuz of operating expenses"
      ],
      correctAnswer: "Net Income cannot be determined - cuz of operating expenses",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "If Company A has a Return on Assets that is much higher than Company B, this could mean that:",
      options: [
        "Company A makes more Net Income than Company B",
        "Company A has fewer assets, perhaps they don’t own things like land or their place of business",
        "Company A’s assets are of lower quality or are older so that their value is less",
        "All are possible explanations"
      ],
      correctAnswer: "All are possible explanations",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "When the Quick Ratio is 1.0, this means:",
      options: [
        "A business can pay off all your liabilities with your current assets",
        "A business can pay off their current assets with their current liabilities",
        "A business can pay off their current liabilities with their total assets",
        "None of the above"
      ],
      correctAnswer: "None of the above",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "If prepaid rent appears above prepaid insurance on the balance sheet, it means:",
      options: [
        "Prepaid rent has a maturity date sooner than prepaid insurance",
        "Prepaid rent has a longer life than prepaid insurance",
        "Prepaid rent is more liquid than prepaid insurance",
        "Prepaid rent is on the wrong financial statement"
      ],
      correctAnswer: "Prepaid rent is more liquid than prepaid insurance",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "Current Portion of Mortgage Payable refers to:",
      options: [
        "An allocation",
        "A portion of the mortgage that is due in the next year",
        "A lesser amount than the mortgage that needs to be paid",
        "All of the above"
      ],
      correctAnswer: "All of the above",
      selectedOption: "",
      feedback: ""
    },
    {
      question: "Purchases are $10,000, Beginning Inventory is $7,000, Ending Inventory is $500, Purchase Discounts are $200, Freight In is $100, Purchase Returns are $150, Freight Out is $600, and Net Sales is $25,000. What is the Gross Profit?",
      options: [
        "$16,250",
        "$8,750",
        "$8,150",
        "None of the above"
      ],
      correctAnswer: "$8,750",
      selectedOption: "",
      feedback: ""
    }

    ];
  
    function checkAnswer(index, option) {
      questions = questions.map((q, i) => 
        i === index ? { ...q, selectedOption: option, feedback: option === q.correctAnswer ? "✅ Correct!" : "❌ Incorrect" } : q
      );
    }
  </script>
  
  <main class="quiz">
    {#each questions as question, index}
      <div class="question-block">
        <h2>{question.question}</h2>
        <div class="options">
          {#each question.options as option}
            <button on:click={() => checkAnswer(index, option)} class:selected={question.selectedOption === option}>
              {option}
            </button>
          {/each}
        </div>
        {#if question.selectedOption}
          <p class="feedback">{question.feedback}</p>
        {/if}
        <hr>
      </div>
    {/each}
  </main>
  
  <style>
    .quiz {
      font-family: Arial, sans-serif;
      text-align: center;
    }
    .question-block {
      margin-bottom: 20px;
      font-size: x-small;
    }
    .options {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-top: 10px;
    }
    button {
      padding: 10px;
      font-size: 16px;
      cursor: pointer;
    }
    .selected {
      background-color: #ddd;
    }
    .feedback {
      margin-top: 15px;
      font-weight: bold;
    }
    hr {
      margin-top: 30px;
      border: 5;
      height: 1px;
      background: #ccc;
    }
  </style>
  