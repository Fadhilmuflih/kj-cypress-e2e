#Example Project

// perubahan
 // input invalid
    cy.get('[data-cy="username-email-input"]').wait(500).type(data[0].INVALID_CMS_EMAIL)
    cy.get('[data-cy="password-input"]').wait(500).type(data[0].INVALID_CMS_PASSWORD)
    cy.get('[data-cy="login-button"]').wait(500).click()