### Company Domain

infisical.com

### What Happened?

- [ ] Silent patch (company fixed the bug but didn’t inform or reward)
- [x] No bounty or swag given
- [ ] Ghosted after submission
- [ ] Other (please explain in summary)

### Summary of the Incident

Deepak Parkash(FancybearIN) reported a valid race condition vulnerability to the Infisical bug bounty program during its public phase. The vulnerability allowed free-tier users to bypass project creation limits by sending concurrent requests, which resulted in unauthorized access to otherwise gated features and effectively bypassed the platform’s subscription logic.

His submission included a full proof of concept (PoC), detailed impact assessment, and step-by-step reproduction instructions. The issue was identified on a live production instance of the platform (https://app.infisical.com), which was explicitly listed as in-scope under their public program.

Despite multiple follow-ups, the report was reclassified as a ‘monetization concern,’ and no bounty was awarded. Shortly after, the public bounty program was moved to an ‘invite-only’ model without clear communication or resolution regarding his disclosure.

### Timeline

The reporter didn’t provide the dates, but I included his case because he shared a full video PoC, which is now public to anyone with the Google Drive link (see below). He is also one of my LinkedIn connections, and this case is based on his experience.

### Proof or Evidence

Google Drive Link - https://drive.google.com/file/d/17ElWmlMVANmfvV_oWGUm97og2CwitCt7/view?usp=drive_link

### Your Handle (optional)

GitHub: [@FancybearIN](https://github.com/FancybearIN)

### Has the company shut down their bug bounty program?

- [ ] Yes, the program has been shut down.
- [ ] No, the program is still active.
- [x] The program has been moved to invite-only.
- [ ] I am not sure about the status.

### Confirmation

- [x] I confirm this is based on my personal experience and is respectful.
