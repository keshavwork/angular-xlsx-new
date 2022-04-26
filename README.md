# ng-xslx

Installation

    bower install --save angular-xlsx-new

Usage

    var result = svc.writeXlsx([
		{
			sheetName: "testSheet",
			columnDefs: [
				{field: "colA", displayName: "Column A"}
			],
			data: [
				{colA: 1}
			]
		}
		]);
