#===------------------------------------------------------------------------===#
#
#                     The KLEE Symbolic Virtual Machine
#
# This file is distributed under the University of Illinois Open Source
# License. See LICENSE.TXT for details.
#
#===------------------------------------------------------------------------===#
klee_add_component(kleaverExpr
	ArrayCache.cpp
	Assigment.cpp
	Constraints.cpp
	ExprBuilder.cpp
	Expr.cpp
	ExprEvaluator.cpp
	ExprPPrinter.cpp
	ExprSMTLIBPrinter.cpp
	ExprUtil.cpp
	ExprVisitor.cpp
	Lexer.cpp
	Parser.cpp
	Updates.cpp
)
