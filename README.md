function doGet() {
  return HtmlService.createHtmlOutputFromFile('index')
      .setTitle('FRAGRANCE PARFUM | San Pedro Sula, Honduras')
      .setXFrameOptionsMode(HtmlService.XFrameOptionsMode.ALLOWALL);
}
